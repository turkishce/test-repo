# HyperFrames GitHub Actions smoke test

This public repository is a minimal, manually triggered test of HyperFrames on
GitHub's hosted Linux runner. It checks the CLI and browser setup, runs the
project check, renders a two-second sample, verifies the MP4 duration, and
stores the result as a short-lived workflow artifact.

Run it from **Actions → HyperFrames smoke test → Run workflow**. The workflow
uses no repository secrets and accepts no user-provided inputs. It does not
access Google Sheets, Drive, or YouTube.
