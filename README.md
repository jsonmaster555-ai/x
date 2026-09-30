<div align="center">

# Relay

### Webhook infrastructure without the headache.

Receive, inspect, route, retry, and monitor webhooks from one powerful desktop app.

[Download for macOS](../../releases/latest) · [Report a Bug](../../issues) · [Request a Feature](../../issues)

</div>

---

## Relay

Relay is a cloud-powered webhook infrastructure platform built around a fast desktop experience.

Instead of digging through logs, building retry systems, or wondering where an event disappeared, Relay gives you one place to see exactly what is happening.

Your infrastructure runs in the cloud.

Relay gives you the control center.

## Features

- **Live Events** — Watch webhook events arrive and get delivered in real time.
- **Automatic Retries** — Failed deliveries can be retried automatically.
- **Event Replay** — Send previous events again without recreating them.
- **Payload Inspector** — Inspect headers, payloads, responses, and metadata.
- **Endpoint Management** — Create and manage webhook destinations.
- **Delivery Logs** — See exactly what happened to every event.
- **Latency Monitoring** — Track webhook delivery performance.
- **Failure Detection** — Quickly find endpoints that are failing.
- **Local Development** — Forward events to applications running locally.
- **MCP Connections** — Connect supported MCP servers and developer tools.
- **Cloud Sync** — Access projects and event history through Relay Cloud.

## How It Works

```text
Your App
    │
    ▼
Relay Cloud
    │
    ├── Receive
    ├── Queue
    ├── Route
    ├── Retry
    ├── Monitor
    │
    ▼
Your Endpoint
