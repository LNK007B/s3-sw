# Static Website on AWS S3

A simple static website hosted on Amazon S3 using static website hosting.

## Tech Stack
- AWS S3
- HTML
- Bucket Policy (IAM/JSON)

## What I Did
1. Created an S3 bucket in REGION-NAME
2. Uploaded `index.html`
3. Enabled static website hosting
4. Added a bucket policy to allow public read access (`s3:GetObject`)
5. Tested the site using the bucket website endpoint

## Bucket Policy Used
Allows public read-only access to objects:
- Effect: Allow
- Principal: *
- Action: s3:GetObject

## What I Learned
- How S3 buckets and objects work
- How bucket policies control access
- Difference between static and dynamic websites

