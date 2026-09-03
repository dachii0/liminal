<p align="center">
  <img src="assets/logo.png" width="96" alt="Tool">
</p>

<h1 align="center">Liminal</h1>
<p align="center">
  <strong>Identity-Aware Web Security Research Platform</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.4.4-ff69b4">
  <img src="https://img.shields.io/badge/Platform-Linux-1793d1">
  <img src="https://img.shields.io/badge/License-Proprietary-red">
  <img src="https://img.shields.io/badge/Availability-Not%20Publicly%20Released-orange">
</p>

Liminal is a closed-source security research platform for web application traffic analysis, interception, authorization testing, and programmable security research.

It observes application behavior across multiple identities and contexts to help identify inconsistencies in access-control boundaries, including horizontal and vertical privilege escalation, cross-identity access, stale sessions, context-dependent bypasses, and parameter manipulation.

> **Availability:** Not publicly released · **Platform:** Linux · **License:** Proprietary

## Features

* Multi-identity authorization analysis
* Behavioral access-control modeling
* Cross-identity request testing
* Authorization boundary analysis
* HTTP/HTTPS interception
* HTTP/1.1 and HTTP/2 support
* Embedded Python editor and executor
* Security testing and exploit libraries exposed through Python APIs
* Context-aware testing payload suggestions
* Attack lab environment
* Header injection and payload manipulation
* Endpoint filtering and blocking
* Over 15 accessible proxy hooks
* Programmable terminal and scripting environment 
* Built-in security hooks 
* Fire-and-forget attack engines 
* Automation 
* Programmable HTTP I/O through user-defined engines and hooks

## Integrated Research Environment

Liminal combines traffic interception, authorization analysis, and programmable testing in a single environment.
The embedded Python runtime allows researchers to inspect and manipulate traffic, automate repetitive testing, and build custom analysis workflows without leaving the proxy.

## Proxy

Liminal includes a custom HTTPS interception proxy developed in Python.
It supports dynamic certificate generation, TLS interception, HTTP/1.1, HTTP/2, and programmable request/response processing.

## Screenshots
<p align="center"> <img src="assets/screen_04.png" width="1000" alt="liminal"> </p>
<p align="center"> <img src="assets/screen.png" width="1000" alt="liminal"> </p>
<p align="center"> <img src="assets/screen_01.png" width="1000" alt="liminal"> </p>


## Responsible Use

Liminal is intended for authorized security testing, penetration testing, research, and controlled environments.


## License

Liminal is proprietary and closed-source. See [`LICENSE`](LICENSE) for the applicable terms.
