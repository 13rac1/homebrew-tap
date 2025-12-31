# Homebrew Tap for 13rac1

This is a [Homebrew tap](https://docs.brew.sh/Taps) containing formulas for 13rac1's projects.

## Installation

```bash
brew tap 13rac1/tap
brew install <formula>
```

## Available Formulas

### cclogs
Claude Code Log Shipper - backup session logs to S3-compatible storage

```bash
brew install 13rac1/tap/cclogs
```

## One-Line Install

You can also install without explicitly tapping:

```bash
brew install 13rac1/tap/cclogs
```

## Updating

Update formulas from this tap:

```bash
brew update
brew upgrade cclogs
```

## About

Formulas in this tap are automatically maintained by [GoReleaser](https://goreleaser.com/) when new releases are published.

## Maintainer Setup

GoReleaser needs a Personal Access Token to push formula updates to this repository.

### Create the Token

1. Go to https://github.com/settings/personal-access-tokens/new
2. Configure:
    - **Token name:** `goreleaser-homebrew-tap`
    - **Expiration:** 1 year (or your preference)
    - **Repository access:** Select "Only select repositories" → choose `homebrew-tap`
    - **Permissions:**
      - **Contents:** Read and write
      - **Metadata:** Read
3. Click **"Generate token"** and copy it

### Add as Repository Secret

1. Go to the 
project repository → **Settings** → **Secrets and variables** → **Actions**
2. Click **"New repository secret"**
3. Name: `HOMEBREW_TAP_GITHUB_TOKEN`
4. Value: Paste the token
5. Click **"Add secret"**
