# bitbucket-pull-request-daemon

This tool informs users over Slack of new open pull requests. It does this as following:
1) Downloads all open BitBucket pull requests for a given repo.
2) Cross-references them with a local array.
3) Informs via slack of any new pull requests.

It was made due to lack of BitBucket webhooks for new pull requests.

To use, you'll need to replace any __template__ variables.
