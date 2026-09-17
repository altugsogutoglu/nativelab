# NativeLab

A native GitLab client for iOS. Built with React Native and Expo.

Review merge requests, triage issues and watch pipelines from a client that feels like it belongs on the phone. Sign in with OAuth to gitlab.com or your own instance. Tokens stay in the iOS Keychain and never touch a third-party server.

[![Download on the App Store](https://img.shields.io/badge/App_Store-Download-000000?logo=apple&logoColor=white)](https://apps.apple.com/us/app/nativelab/id6760226252)
[![Website](https://img.shields.io/badge/nativelab.app-website-FC6D26)](https://nativelab.app)

## Screenshots

Light and dark follow the system setting or a manual choice in Settings.

### Light

<p align="center">
  <img src="screenshots/light/login.png" width="200" alt="Login" />
  <img src="screenshots/light/dashboard.png" width="200" alt="Dashboard" />
  <img src="screenshots/light/projects.png" width="200" alt="Projects" />
  <img src="screenshots/light/activity.png" width="200" alt="Activity" />
</p>

<p align="center">
  <img src="screenshots/light/project-overview.png" width="200" alt="Project overview" />
  <img src="screenshots/light/project-issues.png" width="200" alt="Project issues" />
  <img src="screenshots/light/issue-detail.png" width="200" alt="Issue detail" />
  <img src="screenshots/light/project-merge-requests.png" width="200" alt="Project merge requests" />
</p>

<p align="center">
  <img src="screenshots/light/merge-request-detail.png" width="200" alt="Merge request detail" />
  <img src="screenshots/light/merge-request-changes.png" width="200" alt="Merge request changes" />
  <img src="screenshots/light/merge-request-comments.png" width="200" alt="Merge request comments" />
  <img src="screenshots/light/settings.png" width="200" alt="Settings" />
</p>

### Dark

<p align="center">
  <img src="screenshots/dark/dashboard.png" width="200" alt="Dashboard, dark" />
  <img src="screenshots/dark/projects.png" width="200" alt="Projects, dark" />
  <img src="screenshots/dark/activity.png" width="200" alt="Activity, dark" />
  <img src="screenshots/dark/settings.png" width="200" alt="Settings, dark" />
</p>

<p align="center">
  <img src="screenshots/dark/project-overview.png" width="200" alt="Project overview, dark" />
  <img src="screenshots/dark/project-issues.png" width="200" alt="Project issues, dark" />
  <img src="screenshots/dark/issue-detail.png" width="200" alt="Issue detail, dark" />
  <img src="screenshots/dark/merge-request-changes.png" width="200" alt="Merge request changes, dark" />
</p>

## Features

- **Dashboard**: issues assigned to you, merge requests waiting on your review and recent activity, one screen.
- **Projects**: every project you can reach, with search and owned or starred filters.
- **Issues**: filter by state and label, read the full description, tasks and comments, reply inline.
- **Merge requests**: description, branch pair, pipeline status, reviewers, approvals, a per-file diff viewer and the comment thread.
- **Pipelines**: latest pipeline state on projects and merge requests, with the CI job that failed.
- **Activity**: a feed of what happened across your projects.
- **Themes**: light and dark, both designed on the same neutral palette, with a system option.
- **Text size**: small, medium or large, applied across the whole app.
- **Languages**: English, German, French, Spanish, Portuguese and Turkish.
- **Self-hosted**: works with gitlab.com and any self-hosted GitLab instance over OAuth.
- **Demo mode**: try the app with sample data, no account needed.
- **Privacy**: direct OAuth to your GitLab, no proxy servers, no analytics in the app.

## Requirements

iOS 16 or later. Android is on the roadmap.

## License

All rights reserved.
