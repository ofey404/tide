# TiCode

TiCode is a Visual Studio Code extension that makes developing TiDB a breeze.

Still in the loop of coding, compiling, distributing binary to different servers, restarting every process and pulling information from logs everywhere? Try and see how TiCode makes TiDB development experience great again!

## Features

Do all the things just in your favorite Visual Studio Code:

- Start TiUP Playground/Cluster and start debugging instantly
- Debug TiDB Cluster on Kubernetes
- Run Chaos Mesh experiments

### TODO

- Cluster

  - [x] List all clusters
  - [x] Display a cluster detail inforamtion
  - [x] Start / Stop / Destroy a cluster
  - [ ] Show a cluster topo
  - [x] Open dashboard / grafana
  - Restart
    - [x] Restart a cluster
    - [x] restart all instances of a component
    - [x] restart a single instance
  - Config
    - [x] View a cluster configuration
    - [x] View a single instance configuration
    - [x] Edit and apply a cluster configuration
    - [x] Edit and apply a single instance configuration
  - [x] view all logs of all instances
  - Patch (replace binary)
    - Patch by current repo
      - [x] Patch for all instance of a component
      - [x] Patch for a single instance
    - Patch by other binary
      - [x] Patch for all instance of a component
      - [x] Patch for a single instance
  - [x] SSH to a single instance and enter the folder
  - [ ] Follow logs of all instances @Aylei
  - [ ] Attach to Debug @Aylei

- Playground

  - [x] Start a simple default playground cluster
  - [x] Start a confiured playground cluster
  - [x] Use current repo's binary
  - [x] List playground cluster instances
  - [x] View logs of all instances
  - [x] Follow logs of all instances
  - [ ] Attach to Debug @Aylei

- Bench
  - [ ] Config bench
  - [ ] Start bench

- Kubernetes @Aylei TODO

- Cluster Topo Manager

  - [ ] Manage cluster topos
  - [ ] Deploy a cluster by a topo

- Virtual Machines Manager

  - [ ] Manager vagrant virtual machines
  - [ ] Start virtual machines, ready for deploy a cluster

- Scaffold for adding new feature
  - [ ] Scaffold for tidb-dashboard repo
  - [ ] Scaffold for coprocess

- TiUP Manager
  - [ ] Install TiUP
  - [ ] Upgrade TiUP

## Requirements

TBD

## Extension Settings

## Known Issues

TBD

## Release Notes

### 0.0.1

Initial release
