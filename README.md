Deployment:
 - Local -> GitHub
 - GitHub -> S3 Bucket (via GitHub Actions and AWS Role 'github-deploy')

Email routing:
 - Route 53 -> Cloudflare
 - Cloudflare -> personal inbox

Serving:
 - Route 53 -> Cloudflare
 - Cloudflare -> Cloudfront
 - Cloudfront -> S3 Bucket
