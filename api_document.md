# API Document of BootFiler

## Introduction

This project is set up to manage the files of a website or an APP. It is design to  fit the distributed file system, and developers can just use this project upload, download, share file links with CDN function.

BootFiler uses the RESTFul API standard, for an HTTP URI/URL is your socket to access the file.

## References

## Define

## Design

#### Authenticate

**OAuth2.0 Method**

url:
/api/oath

**JWT Method**

url:
/api/jwt

#### Upload

url:
/api/file

#### Download

url:
/api/file

#### CDN Link

url:
/{file_type}/{date}/filename