# Release Template for XVideos Video Downloader

Use this template when creating new releases to maintain consistency with the established format.

## Release Notes Structure

```markdown
[Brief introductory paragraph about XVideos platform and the tool's purpose]

**Privacy & Security**
- All processing happens locally on your device  
- No data is sent to external servers
- No tracking or analytics
- No personal information collected
- Compatible with private browsing modes

**Legal Notice**
This tool is intended for personal use only. Users are responsible for ensuring their use complies with all applicable laws and the terms of service of the websites they visit. Always respect copyright and intellectual property rights.

# XVideos Video Downloader v[VERSION]

[Brief description of the release and major changes]

## 🚀 Key Features

### Core Download Capabilities
- [List core download features]

### Advanced Technical Features  
- [List technical features and capabilities]

### User Experience
- [List user-facing features and improvements]

## 📋 Requirements

- **Browser**: Chrome or Chromium-based browser (Manifest V3 compatible)
- **License**: Valid license key required (available at [serp.ly/xvideos-downloader](https://serp.ly/xvideos-downloader))
- **Internet Connection**: Required for video detection and download
- **Account**: XVideos account login recommended for premium content access

## 🛠 Installation

### For End Users
1. Purchase a license key from [serp.ly/xvideos-downloader](https://serp.ly/xvideos-downloader)
2. Download the extension package from the [Releases](https://github.com/serpapps/xvideos-video-downloader/releases) section
3. Open Chrome and navigate to `chrome://extensions/`
4. Enable "Developer mode" in the top right corner
5. Click "Load unpacked" and select the extension folder
6. Click the extension icon and enter your email and license key to activate

## 📖 Usage

### Basic Download Process
1. **Navigate** to any XVideos video page
2. **Activate** the extension using your license key (one-time setup)
3. **Download Options**:
   - Click the download button integrated into the video player, OR
   - Click the extension icon in the browser toolbar, OR
   - Right-click on the page and select "Download XVideos Video"
4. **Select Quality** from the available options
5. **Monitor Progress** via the in-page download manager
6. **Access Files** in your default download folder under `XVideos/`

### Supported URL Patterns
- `https://www.xvideos.com/video[video-id]/[title]`
- All XVideos network sites and embedded videos
- XVideos RED premium content (with appropriate account access)

## 🚫 Limitations

- [List current limitations]

## 🔒 Security & Privacy

- [List security and privacy features]

**Disclaimer**: This software is provided for educational and legitimate purposes only. Users must comply with applicable terms of service, copyright laws, data protection regulations, and content policies when implementing these techniques. The authors are not responsible for any misuse of this information.

**Content Warning**: This software addresses adult content platforms. All usage should be conducted in accordance with local laws and institutional policies regarding adult content.
```

## Checklist for New Releases

- [ ] Update version number in all relevant files
- [ ] Update CHANGELOG.md with new version section
- [ ] Test all core functionality
- [ ] Prepare release assets (ZIP file)
- [ ] Update documentation if needed
- [ ] Create GitHub release with this template
- [ ] Verify download links work correctly
- [ ] Update any referenced URLs or links