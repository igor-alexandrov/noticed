### Slack Webhook Delivery Method

Sends a Slack notification via webhook.

`deliver_by :slack_webhook`

##### Options

* `format: :format_for_slack_webhook` - *Optional*

  Use a custom method to define the payload sent to Slack. Method should return a Hash.

* `url: :url_for_slack_webhook` - *Optional*

  Use a custom method to retrieve the Slack Webhook URL. Method should return a String.

  Defaults to `Rails.application.credentials.slack[:notification_url]`


