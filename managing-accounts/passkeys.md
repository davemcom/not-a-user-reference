# Passkeys

A passkey adds a phishing-resistant cryptographic login method, but it does **not automatically remove weaker passwords, SMS, email recovery, or other fallback methods**. The private key stays with the device or passkey provider and is typically protected by hardware-backed security such as Apple's Secure Enclave or a TPM, with Face ID, Touch ID, Windows Hello, or a device PIN authorizing its use. Because the passkey is bound to the real site, a fake site cannot simply trick you into handing it the credential.

* **Private key:** stays with the device/provider.
* **Public key:** stored by the website.
* **Biometrics/PIN:** authorize use of the private key; they are not the key itself.
* **Hardware protection:** usually a secure hardware boundary, though not always a physically separate chip.
* **Phishing resistance:** a passkey for `microsoft.com` is not usable by `micr0soft-login.com`.
* **Important:** account security is still only as strong as the weakest remaining login or recovery path.
