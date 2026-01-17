# Kobo Remote Availability Checker

A GitHub Action that checks the [Kobo Remote](https://pt.kobobooks.com/products/kobo-remote) availability daily and reports the status.

## How it works

- Runs daily at 9:00 AM (Lisbon time)
- Checks the product page for availability
- Reports status in the GitHub Actions Job Summary

## Slack Notifications

To receive Slack notifications when the workflow runs:

1. Go to your desired Slack channel
2. Run: `/github subscribe jduarte/kobo-remote-checker workflows:{event:"completed"}`

## Manual Trigger

You can manually trigger the check from the [Actions tab](../../actions/workflows/check-availability.yml).
