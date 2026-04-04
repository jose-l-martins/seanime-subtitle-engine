# Subtitle Engine (Stable)

A stable fork of the original Seanime Subtitle Engine, optimized for reliability and redundancy.

## Features

- **Double Mirror Redundancy**: Automatic failover between `sub.wyzie.io` (primary) and `sub.wyzie.ru` (fallback) to ensure consistent metadata and subtitle retrieval.
- **Personal API Key Support**: Integrated preference fields for `WyzieKey` and `JimakuKey`.
  - **Wyzie Key**: Primary retrieval method for higher rate limits and personal usage tracking.
  - **Community Fallback**: Seamless fallback to the community key if no personal key is provided or if it fails.
- **Improved Movie Logic**: Fixed manual search issues where anime series metadata would interfere with movie searches.

## Installation

### Method 1: Direct Link (Recommended)

1. Open **Seanime** and navigate to the **Extensions** section in the sidebar.
2. Click the **Add extensions** button at the top right.
3. In the **Install from URL** field, paste the following manifest link:
   ```text
   https://raw.githubusercontent.com/jose-l-martins/seanime-subtitle-engine/main/subtitle-engine-stable/manifest.json
   ```
4. Click **Find** and follow the prompts to install.

### Method 2: Custom Marketplace

This method allows you to see the extension directly in the Marketplace tab along with others.

1. In the **Extensions** page, click the **Marketplace** tab at the top.
2. Click the **Change repository** button (top right).
3. Paste the following Marketplace URL:
   ```text
   https://raw.githubusercontent.com/jose-l-martins/seanime-subtitle-engine/main/marketplace.json
   ```
4. Click **Save**. You should now see **Subtitle Engine (Stable)** in the list.
5. Click the download icon to install.

---
*Based on the original Subtitle Engine by **Thekingcrusher**. Maintained by **jose-l-martins**.*
