# Introduction
> [!NOTE]
> This instruction set assumes that you have already successfully completed a clean install of Ubuntu Server on your VM on GCP

This instruction set will install Discourse inside a Docker container on your VM on GCP.

This installation of Discourse will utilize a Bucket on GCP to store image/file uploads and host the uploads to users via a CDN. This installation will also utilize Mailgun for e-mail functions.

> [!NOTE]
> Currently figuring out how to incorporate an externally run SQL instance on GCP with the Docker instance. This will allow the storage drive capacity of the VM to stay the same and the SQL instance has the feature to automatically increase the database storage size (this will minimize maintenance as the Discourse content increases).
-----
# Instructions

* Needs code
```
Needs code
```
-----
# Conclusion
Discourse is now installed on your VM on GCP and is ready for further configuration via the web UI.
