# System Context

## System Name
Personal Apartment Infastructure

## Purpose

Provide a secure, owner-operated network and compute environment
to support experimentation, automation, and personal infrastructure
services without reliance on external cloud control planes.

## Primary Goals
- Maintain a secure local network perimeter
- Host internal services reliably on consumer hardware
- Support IoT and automation workloads
- Enable safe remote administrative access

## Non-Goals
- Enterprise-grade high availability
- Zero-downtime upgrades
- Multi-site or geographically redundant operation
- Hosting public-facing services

## Stakeholders
- System owner (primary operator)
- Household devices and users (indirect)

## Operating Environment
- Residential apartment
- ISP-provided gateway upstream
- Privately managed internal network and compute resources

## Assumptions & Constraints
- Physical access to hardware is available
- Short service outages are acceptable / tolerable
- Power and cooling are limited by residential constraints
- Security prioritizes prevention over obscurity

## Success Criteria
- Internal services remain accessible during normal operation
- No unintended WAN exposure of internal systems
- System can be recovered manually after failure
