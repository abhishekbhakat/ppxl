# PPXL - Perplexity CLI

Query Perplexity AI directly from your terminal with beautiful formatting.

## Security & Compliance

### Legal Compliance
PPXL operates in full compliance with web service terms and conditions:
- Respects Cloudflare security challenges
- Shows security verification prompts to users when required
- Does not bypass or automate security measures
- Uses standard web protocols and interfaces

### Virus Scan Results
Each release is scanned with multiple antivirus engines. Scan results are available in the release notes.
- [VirusTotal Report](link-to-report)
- [Jotti's malware scan](link-to-scan)

## Installation

### Using Homebrew (macOS)
```bash
brew install ppxl
```

### Manual Installation
1. Download the appropriate binary for your system from the [releases page](../../releases)
2. Make it executable: `chmod +x ppxl`
3. Move to your PATH: `sudo mv ppxl /usr/local/bin/`

## Usage

```bash
# Basic query
ppxl query "your question here"

# Show version
ppxl version

# Enable debug mode
ppxl query --debug "your question here"

# Use custom Chrome path
ppxl query --chrome-path "/path/to/chrome" "your question here"

# Show help
ppxl --help
```

## Features

- Clean, formatted output using Rich
- Table support for structured data
- Error handling with user-friendly messages
- Debug mode for troubleshooting
- Custom Chrome path support

## Support

- For feature requests, please use our [feature request template](.github/ISSUE_TEMPLATE/feature_request.md)
- For bug reports, use our [bug report template](.github/ISSUE_TEMPLATE/bug_report.md)
- For security concerns, see our [security policy](SECURITY.md)

## License

Proprietary. All rights reserved.