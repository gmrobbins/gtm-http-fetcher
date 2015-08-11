GTM HTTP Fetcher makes it easy for Cocoa applications to perform http operations. The fetcher is implemented as a wrapper on NSURLConnection, so its behavior is asynchronous and uses operating-system settings on iOS and Mac OS X.

## Features include:

Simple to build; only one source/header file pair is required
Simple to use: takes just two lines of code to fetch a request
Callbacks are delegate/selector pairs or blocks
Flexible cookie storage
Caching of ETagged responses, reducing overhead of redundant fetches
Automatic retry on errors, with exponential backoff
Support for generating multipart MIME upload streams
Easy, convenient logging of http requests and responses
Fully independent of other projects
To get started with GTM HTTP Fetcher and the Objective-C Client Library, read the introduction.

To browse the fetcher source code, visit the Source tab. Library changes are documented in the release notes. To monitor changes, see the feeds page.

If you have a problem or want a new feature to be included in the fetcher, please join the GTM discussion group or submit an issue.

The fetcher follows the Google Objective-C Style Guide.
