---
swagger: "2.0"
x-collection-name: Ship Station
x-complete: 0
info:
  title: Ship Station Unsubscribe to Webhook
  description: Unsubscribes from a certain webhook.
  version: 1.0.0
host: ssapi.shipstation.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /webhooks/{webhookId}:
    delete:
      summary: Unsubscribe to Webhook
      description: Unsubscribes from a certain webhook.
      operationId: webhooks.webhookId.delete
      x-api-path-slug: webhookswebhookid-delete
      parameters:
      - in: path
        name: webhookId
        description: A unique ID generated by ShipStation and assigned to each webhook
      responses:
        200:
          description: OK
      tags:
      - Unsubscribe
      - To
      - Webhook
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---