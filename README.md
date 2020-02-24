### Forked because original package cannot handle file formats in capital letters (JPG, PNG, JPEG)

# strapi-provider-upload-aws-s3-optimized

Updated to create as many image sizes as you would like. Comma seperate your sizes with 1920x1080 (width x height) format.

Do not add px, it must be formatted just like the example below.

Example Sizes:
1920x1080,1336x768,768x1024,1024x600

The S3 url will have a prefix of your size:
-1920x1080.jpg
-1920x1080.webp

## Installation

```bash
npm install strapi-provider-upload-aws-s3-optimized-caps
```

## Usage

Install and configure: http://localhost:1337/admin/plugins/upload/configurations/development
