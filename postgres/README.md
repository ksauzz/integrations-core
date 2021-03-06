# Postgres Integration

## Overview

Get metrics from postgres service in real time to:

* Visualize and monitor postgres states
* Be notified about postgres failovers and events.

## Setup
### Installation

Install the `dd-check-postgres` package manually or with your favorite configuration manager

### Configuration

Edit the `postgres.yaml` file to point to your server and port, set the masters to monitor

### Validation

When you run `datadog-agent info` you should see something like the following:

    Checks
    ======

        postgres
        -----------
          - instance #0 [OK]
          - Collected 39 metrics, 0 events & 7 service checks

## Compatibility

The postgres check is compatible with all major platforms

## Data Collected
### Metrics
See [metadata.csv](https://github.com/DataDog/integrations-core/blob/master/postgres/metadata.csv) for a list of metrics provided by this integration.

### Events
The Postgres check does not include any event at this time.

### Service Checks
The Postgres check does not include any service check at this time.

## Troubleshooting

If you have any questions about Datadog or a use case our [Docs](https://docs.datadoghq.com/) didn’t mention, we’d love to help! Here’s how you can reach out to us:

### Visit the Knowledge Base

Learn more about what you can do in Datadog on the [Support Knowledge Base](https://datadog.zendesk.com/agent/).

### Web Support

Messages in the [event stream](https://app.datadoghq.com/event/stream) containing **@support-datadog** will reach our Support Team. This is a convenient channel for referencing graph snapshots or a particular event. In addition, we have a livechat service available during the day (EST) from any page within the app.

### By Email

You can also contact our Support Team via email at [support@datadoghq.com](mailto:support@datadoghq.com).

### Over Slack

Reach out to our team and other Datadog users on [Slack](http://chat.datadoghq.com/).

## Further Reading
To get a better idea of how (or why) to have 100x faster Postgres performance by changing 1 line with Datadog, check out our [series of blog posts](https://www.datadoghq.com/blog/100x-faster-postgres-performance-by-changing-1-line/) about it.
