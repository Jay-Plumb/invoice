[![Send Email](https://github.com/Jay-Plumb/invoice/actions/workflows/invoice.yml/badge.svg)](https://github.com/Jay-Plumb/invoice/actions/workflows/invoice.yml)

# Automatic Invoicing

At the end of every month, an invoice is dynamically generated and sent out to the recipient

### Secrets

The following [secrets](https://github.com/Jay-Plumb/invoice/settings/secrets/actions) need to be defined and supplied a value:

| Secret Key         | Notes                                                                                                                                                                                                                  |
| ------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EMAIL_USERNAME     | The email of the sender                                                                                                                                                                                                |
| EMAIL_PASSWORD     | This is not the email password. Create an app password from your email client. For instance, if you are using gmail, head over to `Manage your Google Account` -> search for `app passwords` and create a `custom` app |
| SALARY_GROSS       | The amount to charge the client (gross)                                                                                                                                                                                |
| EMAIL_RECEIVER     | The email receiver                                                                                                                                                                                                     |
| ADDRESS_CONTRACTOR | Address of the contractor                                                                                                                                                                                              |
| ADDRESS_CLIENT     | Address of the client                                                                                                                                                                                                  |
| COMPANY_NAME       | Name of company                                                                                                                                                                                                        |
| EMAIL_BCC          | (optional) The email bcc                                                                                                                                                                                               |
| EXPENSES_LINK      | (optional) Supply a link to your expenses software e.g. [Freeagent](https://www.freeagent.com/en/)                                                                                                                     |

### Dev notes

Check out the following [github actions](https://github.com/marketplace?type=actions)
