# Mattermost Profanity Filter Plugin (Beta)

[![Build Status](https://img.shields.io/circleci/project/github/mattermost/mattermost-plugin-profanity-filter/master.svg)](https://circleci.com/gh/mattermost/mattermost-plugin-profanity-filter)
[![Code Coverage](https://img.shields.io/codecov/c/github/mattermost/mattermost-plugin-profanity-filter/master.svg)](https://codecov.io/gh/mattermost/mattermost-plugin-profanity-filter)
[![Release](https://img.shields.io/github/v/release/mattermost/mattermost-plugin-profanity-filter)](https://github.com/mattermost/mattermost-plugin-profanity-filter/releases/latest)
[![HW](https://img.shields.io/github/issues/mattermost/mattermost-plugin-profanity-filter/Up%20For%20Grabs?color=dark%20green&label=Help%20Wanted)](https://github.com/mattermost/mattermost-plugin-profanity-filter/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc+label%3A%22Up+For+Grabs%22+label%3A%22Help+Wanted%22)


This plugin allows you to censor profanity on your Mattermost server.

**Supported Mattermost Server Versions: 5.2+**

## Installation

1. Go to the [releases page of this Github repository](https://github.com/mattermost/mattermost-plugin-profanity-filter/releases) and download the latest release for your Mattermost server.
2. Upload this file in the Mattermost System Console under **System Console > Plugins > Management** to install the plugin. To learn more about how to upload a plugin, [see the documentation](https://docs.mattermost.com/administration/plugins.html#plugin-uploads).
3. Activate the plugin at **System Console > Plugins > Management**.

### Usage

Inside the `/server` directory, you will find the Go files that make up the server-side of the plugin. Within there, build the plugin like you would any other Go application.

To configure what words are censored on your server, edit the bad words list in **System Console > Plugins > Profanity Filter > Bad words list**.
