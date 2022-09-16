# Novela Hugo theme based blog

https://github.com/forestryio/hugo-theme-novela/

https://hugo-novela-forestry.netlify.app/

## Steps/Todo:
1. Select a blog theme
2. Make changes to the theme appropriately
3. Setup Terraform to provision all the required infrastructure
   1. S3 bucket for static website hosting
   2. ...
4. Setup Jenkins to do:
   1. Trigger a build on commit to frontend (or backend)
   2. Sync the build output to S3 Bucket (Static content)