# ThreatConnect Share Comment Snippets

These are Sublime Text [snippets](docs.sublimetext.info/en/latest/extensibility/snippets.html) for writing share comments in [ThreatConnect](https://app.threatconnect.com/).

## Installation

1. Package Control (*Preferred*)
    1. This package is available on [Package Control](https://packagecontrol.io) under the name "ThreatConnect Share Comments".
2. Manual Installation:
    1. `cd` into your Sublime Text packages directory (see [https://stackoverflow.com/questions/7808452/what-is-the-full-path-to-the-packages-folder-for-sublime-text-2-on-mac-os-lion](https://stackoverflow.com/questions/7808452/what-is-the-full-path-to-the-packages-folder-for-sublime-text-2-on-mac-os-lion) for more details).
    2. Clone this repository:

    `git clone https://github.com/fhightower/threatconnect-share-comment-snippets.git`.

## Available Links

- Groups:
  - Adversaries (`tc-adversary`)
  - Campaigns (`tc-campaign`)
  - Documents (`tc-document`)
  - Emails (`tc-email`)
  - Incidents (`tc-incident`)
  - Signatures (`tc-signature`)
  - Threats (`tc-threat`)
- Indicators:
  - Addresses (`tc-address`)
  - Email Addresses (`tc-emailaddress`)
  - Files (`tc-file`)
  - Hosts (`tc-host`)
  - URLs (`tc-url`)
- Tags (`tc-tag`)
- Tasks (`tc-task`)
- Tracks (`tc-track`)
- Victim (`tc-victim`)
- Tracks (`tc-track`)
- @this (`tc-this`) - this gets converted to the name of the owner into which the comment is posted

## Usage

Each snippet is prefixed with "*tc-*", so just start typing "*tc-*" followed by the indicator, group, or object type to which you would like to link. By default, each of these snippets will position the cursor such that you can type or paste the name/ID of the item to which you are linking. Hitting <TAB> will take you to the end of the snippet so you can continue typing.
