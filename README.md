# chrisschuld.com-images
Public images for chrisschuld.com

Uses S3 sync to make copying images up to S3 easy.

## Syncing with S3 chrisschuld.com
```
aws s3 sync --acl public-read ./images/ s3://chrisschuld.com/images/ --profile chrisschuld.com
```
