# Docker in Docker setup in Kubernetes

This setup is useful for running workloads usually related to CI that has requirements in Docker APIs to be available. Example of this is twistcli. For building docker container it is better to leverage something like kaniko.

Review the [pod spec](dindpod.yaml) for running docker in docker.