# Mastodon RSS Analysis stack module

Content-only Platform Zero module providing curated analysis and commentary feeds and Mastodon bootstrap follows to `mastodon-rss-publisher`.

## Contents

- A reviewed feed definition under `stack.config/mastodon-rss/feeds.d/`.
- A matching bootstrap-follow list under `stack.config/mastodon/bootstrap-follows.d/`.

## Validation

```sh
../sso-stack-generator/scripts/test-module.sh --all .
```

This module has no standalone service; deployed behavior is verified through the publisher.

