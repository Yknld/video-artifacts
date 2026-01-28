# SMRTR Video Artifacts

This repository stores generated educational videos before they're uploaded to Supabase storage.

## Structure

```
videos/
  ├── {lesson_id}_{video_id}.mp4    # Video files
  └── {lesson_id}_{video_id}.json   # Metadata
```

## Process

1. OpenHand generates video
2. Uploads to this repo
3. Polling service downloads and uploads to Supabase
4. Video available in mobile app
