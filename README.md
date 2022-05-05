## imgapi reference

## API

Use this API to perform operations on images

### POST /compress
This endpoint will compress the src image and store it in your bucket
Body request example:
```json
{
  "src":"s3://my-bucket/source.jpg",
  "dst":"s3://my-bucket/dest.jpg",
  "quality": 50,
  "callback":"https://my-website.com/callback"
}
```
