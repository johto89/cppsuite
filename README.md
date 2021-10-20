# cpp_suite

## Installation

### Binary

Simply, download a pre-built binary from [releases page](https://github.com/dwisiswant0/ppfuzz/releases) and run!

### Install Dependencies

To run this:

`
pip3 install -r requirements.txt
`

cpp_suite uses chromiumoxide, which requires Chrome or Chromium browser to be installed. If the CHROME environment variable is set, then it'll use it as the default executable. Otherwise, the filenames google-chrome-stable, chromium, chromium-browser, chrome and chrome-browser are searched for in standard places. If that fails, /Applications/Google Chrome.app/... (on MacOS) or the registry (on Windows) is consulted.

## Usage

It's fairly simple to use cpp_suite!

`
python cpp_suite.py <target_url>
`
