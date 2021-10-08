# High performance live-commerce service

## Overview

At Souzoh, a project to build a live-commerce service has been launched. This service will attract a large number of users in a short period of time as influencers and celebrities sell their premium products.

## Context

We want to build a service which has an advantage in buyer UX. So high-performance is also required even though a large number of users purchase products in a short period of time. Minimizing latency and making customers feel comfortable is a key metric of the system.

## Goal

Meet following requirements:

- 1,000 transactions per sec at peak time
- On the read API to get the remaining stocks, 99 percentile latency is less than 100ms
- On the purchase API, 99 percentile latency is less than 300ms

## Notice

- No need to answer about streaming technology in this topic
- Think about the design in your area of expertise, such as Server side, Client side, Infrastructure, etc
  - Don't have to think of everything
