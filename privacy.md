# Privacy Policy — PostPilot

**Last updated:** June 13, 2026

## Overview

PostPilot is a self-hosted social media scheduling tool developed by Mathias Oversteyns (Oversteyns Collective, Belgium). This policy describes how data is handled within the tool.

## Data Storage

All data is stored locally on the user's own machine:

- **Post metadata** (titles, descriptions, scheduled times) — stored in a local SQLite database (`data/postpilot.db`)
- **Media files** (videos, thumbnails) — stored in a local folder (`uploads/`)
- **Platform credentials** (OAuth tokens, API keys) — stored locally in encrypted form (`data/`)

No data is stored on any remote server operated by the developer.

## Data Shared with Third Parties

When a post is published, PostPilot communicates directly with the relevant platform's official API (e.g. TikTok, YouTube, Instagram). The content and metadata of that post are transmitted to that platform as part of the normal publishing process. This is the only data sharing that occurs.

PostPilot does not share data with any analytics services, advertisers, or other third parties.

## Cookies and Tracking

PostPilot does not use cookies or any form of tracking. It runs entirely on the user's local machine.

## Data Retention

All data remains on the user's local machine and is under the user's full control. The user can delete data at any time by removing the relevant files or database entries.

## Contact

Mathias Oversteyns — oversteyns.collective@gmail.com
