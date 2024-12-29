## AWS CloudFront
- content delivery network (cdn)
- improves read performance, content is cached at the edge
- improves users experience
- 216 point of presence globally (edge locations)
- DDoS protection integration with shield, WAF.

<img width="614" alt="image" src="https://github.com/user-attachments/assets/32f7e3b0-083f-42f3-8bea-537c5331bfc9" />

## CloudFront vs S3 Cross Region Replication
- cloudfront:
  - global edge network
  - file are cached for a TTL
  - great for static content that must be available everywhere
 
- s3 cross region replication
  - must be setup for each region
  - files are updated in near real-time
  - reas-only
  - great for dynamic content that needs to be available for low-latency

