Open Podcasts Data
---

This repository stores configuration data for MIT Open's podcasts ingestion.


#### Podcasts

In order to add a new Podcast channel, create a file with the extention `.yaml` in the `podcasts/` directory. The format of the file should follow this structure:

```yaml
---
rss_url: https://feeds.simplecast.com/w5_4mil2
podcast_title # overrides the title found in the rss feed 
topics: Environmental Studies  # list of topics, optional
offered_by: MIT Climate
website: https://climate.mit.edu/
```

**NOTE:** the comments (the part after `#`) in the example above are purely documentative, you may remove them or leave them in your actual configuration file.
