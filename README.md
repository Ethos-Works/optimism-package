## Welcome to Optimism Package
default package for Optimism
```yaml
optimism_package:
  participants:
    - el_type: op-geth
      el_image: us-docker.pkg.dev/oplabs-tools-artifacts/images/op-geth:latest
      cl_type: op-node
      cl_image: us-docker.pkg.dev/oplabs-tools-artifacts/images/op-node:develop
      count: 1
  network_params:
    network: kurtosis
    network_id: "2151908"
    seconds_per_slot: 2
```