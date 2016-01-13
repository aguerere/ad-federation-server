This is an Security Token Service example that speaks [WS-Federation](http://msdn.microsoft.com/en-us/library/bb498017.aspx) with Saml11 tokens fully implemented in node.js.

Authentication is done against an **Active Directory** or any server that speaks **LDAP**.

This projects uses [node-wsfed](https://github.com/auth0/node-wsfed) and [Passport.js local strategy](http://passportjs.org/guide/username-password/).

This example server can run in two different modes:

- **FORMS** an html form will be shown prompting the user credentials.
- **INTEGRATED** it will use the User variable that IISNode sets for the NTLM authenticated user.

Check Web.config-sample to see the different configuration variables. If you run outside IISNode these are environment variables.

## Issue Reporting

If you have found a bug or if you have a feature request, please report them at this repository issues section. Please do not report security vulnerabilities on the public GitHub issue tracker. The [Responsible Disclosure Program](https://auth0.com/whitehat) details the procedure for disclosing security issues.

## Author

[Auth0](auth0.com)

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more info.
