# static-s3website-code



## Purpose

This repository implements an S3 bucket and CloudFront distribution to serve the static S3 bucket website implemented in repository https://github.com/pahardy/s3static-website-code. It's placeholder html code that could represent a static website. 
The repository also includes a GitLab pipeline file `.gitlab-ci.yml` in order to automatically make changes to the implementation if the html code is amended.

## Obtain the files

```
git clone https://github.com/pahardy/s3static-website-code
```

## Usage
Create a GitLab project, then a GitLab runner. Amending the html code and committing the change will automatically remove the old `index.html` file and upload the newest version.
