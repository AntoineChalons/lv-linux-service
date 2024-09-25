# run your LabVIEW built app as a service on Linux

## Why creating a service?

1. [Automatic Startup](why.md#automatic-startup)
2. [Run Without User Login](why.md#run-without-user-login)
3. [Process Management](why.md#process-management)
4. [Resource Control](why.md#resource-control)
5. [Enhanced Security](why.md#enhanced-security)
6. [Dependency Management](why.md#dependency-management)
7. [Logging and Monitoring](why.md#logging-and-monitoring)
8. [Standardized Control](why.md#standardized-control)
9. [Scalability](why.md#scalability)
10. [System Integration](why.md#system-integration)
11. [Easier Maintenance](why.md#easier-maintenance)

## What is systemd

![systemd](img/logo-systemd.png)

Check the doc on [www.systemd.io](www.systemd.io)

systemd is

    - A system and service manager for Linux operating systems.

    - The default initialization system (init system) for most major Linux distributions.
    
    - A software suite that provides various system components and utilities.

Key points about systemd

    - It 's the first process started during boot (PID 1) and the last one terminated during shutdown.
    
    - It manages the startup and shutdown of other system services and processes.
    
    - It unifies service configuration and behavior across Linux distributions.
    
    - It provides features like parallel boot processes, on-demand starting of daemons, and dependency management between services.

## How to compile my app as a service using LabVIEW

### Build a shared library

### Write a c wrapper

### Configure your service with systemd