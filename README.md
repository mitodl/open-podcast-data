## Open Podcasts Data

This repository stores configuration data for MIT Open's podcasts ingestion.

#### Podcasts

In order to add a new Podcast channel, create a file with the extention `.yaml` in the `podcasts/` directory. The format of the file should follow this structure:

```yaml
---
rss_url: https://feeds.simplecast.com/7xNsi2o4
topics: Political Science,Social Science,Society
offered_by: J-PAL North America
website: https://www.povertyactionlab.org/page/j-pal-voices-impact-and-promise-summer-jobs-united-states
google_podcasts_url: https://podcasts.google.com/feed/aHR0cHM6Ly9mZWVkcy5zaW1wbGVjYXN0LmNvbS83eE5zaTJvNA==
apple_podcasts_url: https://podcasts.apple.com/us/podcast/j-pal-voices/id1533342048
```

**NOTE:** the comments (the part after `#`) in the example above are purely documentative, you may remove them or leave them in your actual configuration file.
