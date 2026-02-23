# Architecture

## Purpose

agent-infra-cyber-sync-worker-iot-d1w evaluates device telemetry and operational anomalies to improve fleet reliability and safety.

## Components

- Signal intake layer
- Assessment engine
- Output formatter for downstream automation

## Runtime Flow

1. Receive signal text/event.
2. Compute deterministic risk score.
3. Emit structured assessment result.
