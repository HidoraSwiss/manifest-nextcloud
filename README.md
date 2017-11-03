![Nextcloud](images/nextcloud-round.png)

## Nextcloud

Nextcloud puts your data at your fingertips, under your control.
Store your documents, calendar, contacts and photos on your Jelastic plateform.

More info on [https://nextcloud.com/](https://nextcloud.com/)

## Deploy Nextcloud on Hidora in 3 minutes

This is a quick tutorial to explain how to quickly deploy a [Nextcloud](https://nextcloud.com/) server on Hidora (or any other [Jelastic provider](https://jelastic.cloud/)).

1. On the Jelastic console, click on `Import` and select the URL tab.
2. Paste this URL in the input field : https://raw.githubusercontent.com/HidoraSwiss/manifest-nextcloud/master/manifest.jps and click on `Import`.
3. Provide an environnment name and a display name for your new environnement and then click on `Install`.

Few minutes later, your new Nextcloud server is fully installed and you can start to manage some files with your team.

> If you need a secure connection over SSL/TLS, you can easily add it by the *topology panel* corresponding to your envrionnement and click on `SSL` to enable it. Then, when you click on `Apply`, your environnement is reconfigured to use HTTPS.
