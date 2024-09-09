# EPP Registrar Module for FOSSBilling (Nic.ge)

## Compatibility

This module is designed for use with Nic.ge registry - .ge extension.

# FOSSBilling Module Installation instructions

## 1. Download and Install FOSSBilling:

Start by downloading the latest version of FOSSBilling from the official website (https://fossbilling.org/). Follow the provided instructions to install it.

## 2. Installation and Configuration of Registrar Adapter:

First, download this repository which contains the NicGe.php file. After successfully downloading the repository, move the NicGe.php file into the `[FOSSBilling]/library/Registrar/Adapter` directory.

## 3. Activate the Domain Registrar Module:

Within FOSSBilling, go to **System -> Domain Registration -> New Domain Registrar** and activate the new domain registrar.

## 4. Registrar Configuration:

Next, head to the "**Registrars**" tab. Here, you'll need to enter your specific configuration details, including the path to your SSL certificate and key.

## 5. Adding a New TLD:

Finally, add a new Top Level Domain (TLD) using your module from the "**New Top Level Domain**" tab. Make sure to configure all necessary details, such as pricing, within this tab.

# Troubleshooting

If you experience problems connecting to your EPP server, follow these steps:

1. Ensure your server's IP (IPv4 and IPv6) is whitelisted by the EPP server.

2. Confirm your client and server support IPv6 if required. If needed, disable IPv6 support in EPP server.

3. Reload the EPP module or restart the web server after any changes.

4. Ensure certificates have the correct permissions: `chown www-data:www-data cert.pem` and `chown www-data:www-data key.pem`.

5. Verify the EPP module is configured with the chosen registrar prefix.