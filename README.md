# EPB static pages

This is the repo for the various static pages we use. 

The only thing currently in use are the static error pages.

## EPB static error pages

When the service goes down, we can intercept the errors in cloudfront and point to our own static error pages hosted in S3, rather than serving the generic AWS error pages.

These provide some information on how to contact us, and keeps the branding consistent.

The error pages are the same across environments, so all variants are tracked in the main branch of this repo.

If you make changes, you will need to upload the directories and their files to the error pages es3 buckets in each AWS account either via the console or the cli.

## EPB static start pages

**NO LONGER IN USE**
