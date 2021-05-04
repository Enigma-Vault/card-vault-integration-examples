# Integration-Examples
There are multiple ways to integreate your app with Enigma Vault's Card Vault: simple iframe, advanced iframe, popup, and redirect.

## Advanced iframe integration
[Link to example](https://github.com/Enigma-Vault/card-vault-integration-examples/blob/15852c71750acc5276b4ab3e642c4602e6df319b/embedFormForControl/parent.html)

Using the advanced iframe integration, your app has full control over the submission of the Enigma Vault card store form. Using the postMessage method within the browser's windows API, your parent page informs the iframed card store form when it should submit. After submission, the card store form returns an object on success or failure back through the windows API.
