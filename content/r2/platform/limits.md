---
title: Limits
pcx-content-type: concept
---

# Limits

## Account plan limits

{{<table-wrap>}}

| Feature                       | Limit                                 |
| ----------------------------- | ------------------------------------- |
| Bucket                        | 1000 buckets per account              |
| Data storage per bucket       | Unlimited                             |
| Object size                   | 5 TB per object<sup>1</sup>           |
| Max upload size<sup>3</sup>   | 5 GB<sup>2</sup>                      |
| Class A Operations per bucket | 1000 per second<sup>4</sup>           |
| Class B Operations per bucket | 250 per second<sup>4</sup>            |

{{</table-wrap>}}

1. The object size limit is 5 GB less than 5 TB, so 4.995 TB.
2. The max upload size is 5 MB less than 5 GB, so 4.995 GB.
3. Max upload size applies to uploading a file via one request, uploading a part of a multipart upload, or
copying into a part of a multipart upload. If you have a Worker, its inbound request size is
constrained by [Workers limits](/workers/platform/limits). The max upload size limit does not apply to subrequests.
4. During Open Beta, we will restrict the number of operations per bucket.

To increase these limits, contact your Cloudflare account team.
