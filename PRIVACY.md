# Privacy Policy — numlo uploader

_Last updated: 15 November 2026_

**numlo** is a private, single-user desktop application that publishes videos to the YouTube channels
[@numlo_ru](https://www.youtube.com/@numlo_ru) and [@numlo_en](https://www.youtube.com/@numlo_en), both owned by the
developer of the application. It is not offered to the public and has no users other than the channel owner.

## What the app accesses

The app uses the YouTube Data API with two scopes:

- `youtube.upload` — to upload videos and set their title, description, tags and privacy status on the owner's channels;
- `youtube.readonly` — to read the channel's name and handle, so that a video is never uploaded to the wrong channel.

It does not read comments, subscribers, viewer data or any information about other people.

## What is stored and where

- OAuth tokens issued by Google are stored only on the owner's own computer, in a local folder excluded from version
  control. They are never transmitted anywhere except to Google's API endpoints.
- The app keeps a local database of its own videos (titles, publication status, YouTube video ids, production costs).
- No personal data of viewers or third parties is collected, stored or processed.

## Sharing

Nothing is shared with third parties. The app's use of information received from Google APIs adheres to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy),
including the Limited Use requirements.

## Revoking access

Access can be revoked at any time at https://myaccount.google.com/permissions or by deleting the local token files.

## Contact

Questions about this policy: open an issue in this repository.
