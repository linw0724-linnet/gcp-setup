# Introduction
> [!NOTE]
> This instruction set assumes that you have already successfully completed a clean install of Ubuntu Server on your VM on GCP.

This instruction set will install Snipe-It inside a Docker container on your VM on GCP.

This installation of Snipe-It will utilize a Bucket on GCP to store image/file uploads and utilize Mailgun for e-mail functions.

> [!WARNING]
> Currently figuring out how to incorporate an externally run mySQL instance on GCP with the Docker instance instead of on AWS or Azure. This will allow the storage drive capacity of the VM to stay the same and the mySQL instance has the feature to automatically increase the database storage size (this will minimize maintenance as the database size increases).

> [!WARNING]
> Currently figuring out how to use GCP S3 for image/file uploads instead of on AWS or Azure.

> [!WARNING]
> Currently figuring out how to incorporate Mailgun for e-mail functionality.

> [!WARNING]
> Currently figuring out how to enable barcode generation using GD Library or Imagemagick.

> [!WARNING]
> Associated `docker-compose.yml`, `my_env_file`, and `my_standalone_env_file` file content needs to be updated and verified.
-----
# Instructions

> [!WARNING]
> Further instructions needed.
-----
# Conclusion
Snipe-It is now installed on your VM on GCP and is ready for further configuration via the web UI.
