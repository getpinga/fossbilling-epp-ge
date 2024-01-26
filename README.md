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
