# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [v1.0.0] - 2024-12-01

XVideos is one of the world's largest adult entertainment platforms, hosting millions of videos across various categories and performers. While the platform offers streaming access to content, it doesn't provide built-in download functionality for users who want to save content for offline viewing.

This extension bridges that gap by providing a simple, privacy-focused way to download videos you have access to, ensuring you can enjoy your favorite content anytime, anywhere, without requiring an internet connection.

**Privacy & Security**
- All processing happens locally on your device
- No data is sent to external servers
- No tracking or analytics
- No personal information collected
- Compatible with private browsing modes

**Legal Notice**
This tool is intended for personal use only. Users are responsible for ensuring their use complies with all applicable laws and the terms of service of the websites they visit. Always respect copyright and intellectual property rights.

# XVideos Video Downloader

A professional Chrome extension that enables seamless video downloads from XVideos with advanced features including license activation, refresh-proof downloads, and real-time progress tracking.

## 🚀 Key Features

### Core Download Capabilities
- **XVideos Platform Support**: Downloads from XVideos.com including premium RED content
- **Multiple Quality Options**: Supports 480p, 720p, 1080p, and 4K resolution when available
- **Format Flexibility**: Handles both direct MP4, WebM, and FLV video formats
- **Refresh-Proof Downloads**: Downloads continue even if you navigate away or refresh the page
- **Real-Time Progress**: Live progress tracking with percentage, file size, and download speed

### Advanced Technical Features
- **Stream Pattern Analysis**: Advanced video data extraction from page JavaScript variables
- **CDN Failover Strategy**: Sophisticated CDN endpoint detection and failover mechanisms
- **yt-dlp Integration**: Leverages yt-dlp for robust video extraction and processing
- **FFmpeg Processing**: Advanced video processing, analysis, and format conversion capabilities
- **HLS Pipeline**: Support for HLS/M3U8 segmented video formats with automatic concatenation
- **Context Menu Integration**: Right-click download option on any supported video page

### User Experience
- **License Activation System**: Secure license verification system
- **In-Page UI**: Integrated download button directly on the video player
- **Download Manager**: Comprehensive progress tracking with cancel/retry options
- **Smart Filename Handling**: Automatic filename sanitization and organization
- **Organized Storage**: Downloads saved to dedicated `XVideos/` folder
- **Batch Processing**: Support for multiple video downloads with queue management

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

### Advanced Features
- **Batch Download**: Queue multiple videos for sequential download
- **Smart Recovery**: Resume interrupted downloads automatically
- **Quality Selection**: Choose from available resolutions (480p, 720p, 1080p, 4K)
- **Format Conversion**: Automatic format optimization for compatibility
- **Duplicate Detection**: Prevent downloading the same video multiple times
- **Bandwidth Management**: Control download speeds and scheduling

## 🔧 Technologies

- **JavaScript**: Core extension logic and user interface
- **Node.js**: Backend processing and automation workflows
- **Browser Extension**: Chrome Manifest V3 architecture
- **FFmpeg**: Video processing, analysis, and format conversion
- **yt-dlp**: Advanced video extraction and download capabilities

## 🚫 Limitations

- **Single Video Downloads**: Primary focus on individual video processing
- **Chrome Only**: Requires Manifest V3 compatible browser
- **License Required**: Activation gate prevents unauthorized use
- **Network Dependent**: Requires internet connection for all operations
- **No Live Streams**: On-demand video content only
- **XVideos Network Only**: Limited to supported XVideos domains
- **No Subtitle Support**: Video tracks only, no subtitle extraction

## 🔒 Security & Privacy

- **License Verification**: Secure API-based activation system
- **Local Storage**: Minimal data stored locally (activation status only)
- **No Data Collection**: Extension doesn't collect or transmit user data
- **Domain Restricted**: Permissions limited to necessary domains only
- **Secure Communication**: All API calls use HTTPS
- **Privacy Protection**: Built-in privacy protection and secure downloading
- **File Integrity**: Secure download verification and file integrity checks

## 🐛 Troubleshooting

### Common Issues and Solutions

#### Download Failures
- Check your internet connection if downloads fail
- Verify the video URL is correct and accessible
- Update your downloader software to the latest version
- Clear browser cache and cookies if experiencing issues
- Try a different download format or quality setting

#### Performance Issues
- Slow downloads may indicate network congestion
- Try limiting concurrent downloads
- Use lower quality settings for faster downloads
- Check available disk space

#### Quality and Integrity Issues
- Verify video file integrity after download
- Use built-in repair tools for corrupted files
- Re-download if integrity checks fail
- Report persistent issues via GitHub Issues

## 📞 Support

- 🐛 Report bugs [here](https://github.com/serpapps/xvideos-video-downloader/issues)
- 🆕 Request features [here](https://github.com/serpapps/xvideos-video-downloader/issues)
- ❓ Check FAQs [here](https://github.com/orgs/serpapps/discussions/categories/faq)
- 💬 [Community Support](https://serp.ly/@serp/community)

**Disclaimer**: This software is provided for educational and legitimate purposes only. Users must comply with applicable terms of service, copyright laws, data protection regulations, and content policies when implementing these techniques. The authors are not responsible for any misuse of this information.

**Content Warning**: This software addresses adult content platforms. All usage should be conducted in accordance with local laws and institutional policies regarding adult content.

**Last Updated**: December 2024  
**Version**: 1.0.0  
**Next Review**: March 2025