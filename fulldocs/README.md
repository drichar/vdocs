Full documentation
---

The documentation is designed in such a way that it can be read like a book - it has a "recommended reading order" and each "page" links to the next one in the sequence. This is ideal for those new to Pixwel.

[Follow the recommended reading plan by starting here >>](/docs/recommended-reading.md)

Alternatively, you can dive straight in to any topic using the tree below:

* [Recommended reading](/docs/recommended-reading.md) - useful things to read before starting on Pixwel.
* [Architecture](/docs/architecture.md) - the overall structure of Pixwel.
* [Pixwel UI](/docs/ui/README.md) - User interface.
  * [Pixwel UI - unit testing](/docs/ui/testing.md) - User interface.
  * [Pixwel UI - grunt build pipeline](/docs/ui/grunt.md) - User interface.
  * [Pixwel UI - jwplayer video player](/docs/ui/videoplayer.md) - including how to test videos locally.
* [Pixwel API](/docs/README.md) - API.
  * [Pixwel API - database](/docs/api/database.md) - Getting real data into the API.
  * [Pixwel API - testing](/docs/api/testing.md) - Unit testing the Pixwel API
  * [Pixwel API - xdebug](/docs/api/xdebug.md) - Using XDebug with the API.
  * [Pixwel API - static analysis](/docs/api/static-analysis.md) - Syntax checking.
  * [Pixwel API - troubleshooting](/docs/api/troubleshooting.md) - API troubleshooting. Simply a dump of problems we've had and solutions/workarounds.
* [Infrastructure](/docs/infrastructure.md) - overview of the Pixwel AWS setup.
* [SSL](/docs/ssl.md) - SSL certs, configuration of the load balancer, updating and testing.
* [Sessions](/docs/sessions.md) - How does the Pixwel platform manage sessions? How are the expired?
* [Services](/docs/services.md) - Linux services that run on Pixwel nodes - workers, upstart jobs, cron, etc cetera.
* [Search](/docs/search.md) - The Pixwel search, provided by ElasticSearch.
* [SSH](/docs/ssh.md) - how to access instances.
* [Caching](/docs/caching.md) - how Pixwel uses the cache and how to troubleshoot it.
* [Flags (new and updated tags)](/docs/flags.md) - how the new and updated tags are applied to the catalog.
* [Email docs](/docs/email.md) - how messages are batched and sent.
* [MailDev docs](/docs/maildev.md) - developing email functionality for Pixwel.
* [Slurpee](/docs/slurpee.md) - the classic, on-site importer for Pixwel, including how to test.
* [Slurpee 1.5 AKA Ingest](/ingest/README.md) - the new version of Slurpee - drag and drop with Lambda, FFPrope and FFMPEG.
* [Slurpee 2](/slurpee2/README.md) - latest and greatest Slurpee.
* [Offline](/docs/offlines.md) - offlines for work requests, including how to test.
* [i18n](/docs/i18n.md) - translations/internationalisation. How to make Pixwel not be in English.
* [Faye - real time messaging](/docs/faye.md) - sends messages to the logged in users. Uses immutable infrastructure to manage notifications.pixwel.com
* [Logging](/docs/logs-and-telemetry.md) - Where are the logs? Other telemetry.
* [Alarms](/docs/alarms.md) - How we know about and respond to problems before they become serious.
* [Profiling with XHProf](/docs/xhprof.md) - analysing the code, memory, et cetera.
* [Pull requests](/docs/pull-requests.md) - how to submit code to Pixwel. Features a bookmarklet to make it easier.
* [Releases](/docs/releases.md) - how to perform a production release.
* [Aspera](docs/aspera.md) - how the file transfer component is integrated.
* [Manual test scripts](/docs/manual-test-scripts.md) - index of pull requests which contain useful test scripts.
