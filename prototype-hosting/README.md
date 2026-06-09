# Prototype Hosting

This folder is for long-term product prototype hosting.

## Structure

- `current/` contains the latest prototype. Share this URL with engineers for the newest version.
- `archive/` contains dated snapshots for review and comparison.

## Update Flow

1. Replace `current/index.html` with the latest prototype.
2. Copy the same file into a new dated archive folder when you want to keep a version.
3. Upload this folder to Tencent CloudBase Static Website Hosting.

## Suggested URLs

- Latest: `/current/`
- Archive: `/archive/2026-06-08-v1/`

## CloudBase Notes

Use Tencent CloudBase Static Website Hosting for stable access from mainland China.

The first setup requires:

- A Tencent Cloud account
- Real-name verification
- A CloudBase environment
- Static website hosting enabled

After setup, you can upload the contents of this folder through the CloudBase console or CLI.
