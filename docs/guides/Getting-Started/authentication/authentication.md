---
title: "Authentication"
slug: "authentication"
hidden: false
createdAt: "2020-01-15T18:58:34.836Z"
updatedAt: "2022-12-13T18:43:56.137Z"
seeAlso:
 - "api-authentication-using-application-keys"
 - "app-authentication-using-auth-tokens"
 - "user-authentication-and-login"
---
Authentication is a crucial aspect of API integrations, backend, and frontend app development. It ensures authorized access by requiring valid credentials like API keys or tokens. This shields sensitive data, prevents breaches, and builds user trust. Get started with VTEX authentication for developers with the following guides:

- [API authentication using application keys](https://developers.vtex.com/docs/guides/api-authentication-using-application-keys)
- [App authentication using auth tokens](https://developers.vtex.com/docs/guides/app-authentication-using-auth-tokens)
- [User authentication and login](https://developers.vtex.com/docs/guides/user-authentication-and-login)

There are different contexts in which authentication is required in the regular functioning of a VTEX store. Below are some example use cases and the recommended authentication methods.

| **Use case** | **Indicated authentication methods** |
| ----- | ----- |
| Backend VTEX IO app | [User token](https://developers.vtex.com/docs/guides/user-authentication-and-login) via VTEX IO context, or, if needed, [app authentication token](https://developers.vtex.com/docs/guides/app-authentication-using-auth-tokens) via VTEX IO context |
| Frontend VTEX IO app | [User token](https://developers.vtex.com/docs/guides/user-authentication-and-login) via VTEX IO context |
| Self-hosted backend request to VTEX APIs | [Application keys](https://developers.vtex.com/docs/guides/api-authentication-using-application-keys) |
| Self-hosted frontend request to VTEX APIs | [User token](https://developers.vtex.com/docs/guides/user-authentication-and-login) |

## Learn more

- **Authorization**: [Users](https://help.vtex.com/en/subcategory/users--63DHe3VQEEE6Uuua8gIs2M), [Roles](https://help.vtex.com/en/tutorial/roles--7HKK5Uau2H6wxE1rH5oRbc) and [License Manager Resources](https://help.vtex.com/en/tutorial/license-manager-resources--3q6ztrC8YynQf6rdc6euk3)
- **Auditability**: [Audit](https://help.vtex.com/en/tutorial/searching-for-events-on-audit--5RXf9WJ5YLFBcS8q8KcxTA)