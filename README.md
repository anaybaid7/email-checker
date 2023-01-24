# email-validator
Checks validity of Emails 

# Email Status
A simple webpage to check if an email address exists or not.

### Example
| Input                 | Output    | Meaning                        |
| --------------------- | :-------- | -------                        |
| anaybaid1.00x@gmail.com      | Green     | Email exists                   |
| anaybaidd@gmail.com | Red       | Email does not exist           |
| hafaxohubi@larjem.com | Yellow    | Email exists but is disposable |

### Workable Implementation: 
The script requests data from the [Mailboxlayer API](https://mailboxlayer.com), a REST API which validates and verifies email addresses.
If an email address exists the page turns green, otherwise it turns red. If the API detects that the email address exists but is disposable, the page turns yellow.
