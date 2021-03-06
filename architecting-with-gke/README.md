# Architecting With GKE

- [Quick Overview of the object types](https://medium.com/hashmapinc/30-second-kubernetes-concepts-cheat-sheet-98ba813194cb)
- [Useful KubeCTL Cheat Sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)
- [Nice Definitions of Each of the Workloads](https://www.freecodecamp.org/news/a-friendly-introduction-to-kubernetes-670c50ce4542/)
- [Kubernetes from scratch by Kelsey Hightower](https://github.com/kelseyhightower/kubernetes-the-hard-way)
- [Medium post on fully private clusters](https://medium.com/google-cloud/completely-private-gke-clusters-with-no-internet-connectivity-945fffae1ccd). Slightly outdated as some of the underlying technology has been updated to be included within GKE.
- [Google post on private clusters](https://cloud.google.com/kubernetes-engine/docs/how-to/private-clusters). Some of the updates to the previous blog can be found here.
- Confluence on running [Kafka in Kubernetes](https://www.confluent.io/blog/apache-kafka-kubernetes-could-you-should-you)
- [Spark on Kubernetes](https://spark.apache.org/docs/latest/running-on-kubernetes.html)
- Securing Docker with [runsc/gVisor](https://github.com/google/gvisor). This takes a bit of work to run on a mac but nice to put through its paces.
- [Windows Pods](https://cloud.google.com/blog/products/containers-kubernetes/how-to-deploy-a-windows-container-on-google-kubernetes-engine)
- Location of the [stable helm charts](https://github.com/helm/charts) if you want to edit them or create your own
- [Skaffold](https://skaffold.dev/) Automated deployment of code to kubernetes for rapid dev cycle. This has both a production `skaffold run` variant as well as a rapid dev focused `skaffold dev` option.
