# Identity library

This Ms-Identity-Python library is an authentication/authorization library that:

* Suitable for apps that are targeting end users on
  [Microsoft identity platform, a.k.a. Microsoft Entra ID](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-overview)
  (which includes Work or school accounts provisioned through Azure AD,
  and Personal Microsoft accounts such as Skype, Xbox, Outlook.com).
* Currently designed for web apps,
  regardless of which Python web framework you are using.
* Provides a set of high level API that is built on top of, and easier to be used than
  [Microsoft's MSAL Python library](https://github.com/AzureAD/microsoft-authentication-library-for-python).
* Written in Python, for Python apps.


## Installation

This package is only hosted on GitHub.
To install it, you need to use one of the following commands.

Choose the package declaration that matches your web framework:

* Django:

      pip install "ms_identity_python[django] @ git+https://github.com/azure-samples/ms-identity-python@0.9"

* Flask:

      pip install "ms_identity_python[flask] @ git+https://github.com/azure-samples/ms-identity-python@0.9"

* Quart:

      pip install "ms_identity_python[quart] @ git+https://github.com/azure-samples/ms-identity-python@0.9"

