# Buzz Recipe Importer

Create Algolia index from YouTube

# Requirement

- Python 3.x or Docker

# Setup

- Set Your Environment Info in `.env`
  - `DEVELOPER_KEY`
    - YouTube Data API KEY, https://developers.google.com/youtube/v3/getting-started
  - `ALGOLIA_APPLICATOIN_ID`
  - `ALGOLIA_ADMIN_API_KEY`
  - `ALGOLIA_INDEX_NAME`
    - Algolia https://www.algolia.com/doc/guides/getting-started/quick-start/

# Usage

local

> pip install -r requirements.txt && python app.py <channel_id>

Docker

> make build && make run <channeld_id>

last updated: 2023/4/24
