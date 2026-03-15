Deployment:
 - Local -> GitHub
 - GitHub -> S3 Bucket (via GitHub Actions and AWS Role 'github-deploy')

Email (Incoming)
 - Route 53 -> Cloudflare
 - Cloudflare -> personal Gmail inbox

Email (Outgoing)
 - Gmail -> Gmail's SMTP servers (personal account 'send mail as')

Serving:
 - Route 53 -> Cloudflare
 - Cloudflare -> Cloudfront
 - Cloudfront -> S3 Bucket
