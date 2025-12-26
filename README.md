# 03 Automation Platforms

Platform automation and integration tools for YouTube, social media, web scraping, and API integrations.

## Structure

```
03_automation_platforms/
├── api_integrations/          # Third-party API integrations
├── social_media_automation/   # Social media platform automation
├── web_automation/            # Web scraping and automation
├── youtube_automation/        # YouTube content automation
├── __init__.py                # Package initialization
├── config.py                  # Configuration settings
├── utils.py                   # Utility functions
├── proxy_harvester.py         # Proxy harvesting utilities
├── logo.py                    # Logo/branding utilities
└── about.py                   # About/info utilities
```

## Subcategories

### YouTube Automation

YouTube content automation, upload, and management tools.

### Social Media Automation

Automation tools for various social media platforms.

### Web Automation

Web scraping, browser automation, and web interaction tools.

### API Integrations

Third-party API integration wrappers and utilities.

## Core Modules

- **config.py** - Configuration and settings
- **utils.py** - Shared utility functions
- **proxy_harvester.py** - Proxy server harvesting and management
- **logo.py** - Logo and branding utilities
- **about.py** - About and information utilities

## Usage

```python
from automation_platforms import config, utils
from automation_platforms.youtube_automation import upload_video
from automation_platforms.social_media_automation import post_to_twitter
from automation_platforms.api_integrations import call_api
```

## Notes

- Consolidated directories have been merged into main files
- All versions have been archived to `08_archived/consolidated/`
- Backup files have been moved to archive
