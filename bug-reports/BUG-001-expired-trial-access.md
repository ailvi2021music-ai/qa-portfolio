# BUG-001: Paid content is accessible with expired Trial subscription

## Summary
Paid content is accessible when Trial subscription has expired.

## Preconditions
- User is authorized
- Subscription status: Trial
- Trial period is expired
- User is on the main page

## Steps to Reproduce
1. Click "Open paid content"

## Actual Result
Paid content page is opened.

## Expected Result
Access should be denied and an error message "Subscription is inactive" should be displayed.

## Notes
- Issue may be related to backend access control.
- Requires verification on API level.
