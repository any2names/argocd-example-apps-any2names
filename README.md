# Argo CD Example Apps

This repository contains example applications for demoing Argo CD functionality. Feel free
to register this repository to your ArgoCD instance, or fork this repo and push your own commits
to explore Argo CD and GitOps!

| Argo CD                                                       | Application                                        | Description                                                                                                                                                                                                              |
| ------------------------------------------------------------- | -------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [apps][app_sync_example_apps]                                 | [apps](apps/)                                      | An app composed of other apps synchronized in [Argo CD][app_sync_example_apps]                                                                                                                                           |
| [example.applicationset][app_applicationset]                  | [applicationset](applicationset/)                  | One example per ApplicationSet generator type (List, Cluster, Git, Matrix, Merge, Pull Request), including an intentionally-broken Git generator, progressive sync example, and ApplicationSet in any namespace examples |
| [example.blue-green][app_blue_green]                          | [blue-green](blue-green/)                          | Demonstrates how to implement blue-green deployment using [Argo Rollouts](https://github.com/argoproj/argo-rollouts)                                                                                                     |
| [example.guestbook][app_guestbook]                            | [guestbook](guestbook/)                            | A hello word guestbook app as plain YAML                                                                                                                                                                                 |
| [example.helm-dependency][app_helm_dependency]                | [helm-dependency](helm-dependency/)                | Demonstrates how to customize an OTS (off-the-shelf) helm chart from an upstream repo                                                                                                                                    |
| [example.helm-guestbook][app_helm_guestbook]                  | [helm-guestbook](helm-guestbook/)                  | The guestbook app as a Helm chart                                                                                                                                                                                        |
| [example.helm-hooks][app_helm_hooks]                          | [helm-hooks](helm-hooks/)                          | An application with native Helm hooks                                                                                                                                                                                    |
| [example.jsonnet-guestbook][app_jsonnet_guestbook]            | [jsonnet-guestbook](jsonnet-guestbook/)            | The guestbook app as a raw jsonnet                                                                                                                                                                                       |
| [example.jsonnet-guestbook-tla][app_jsonnet_guestbook_tla]    | [jsonnet-guestbook-tla](jsonnet-guestbook-tla/)    | The guestbook app as a raw jsonnet with support for top level arguments                                                                                                                                                  |
| [example.kustomize-guestbook][app_kustomize_guestbook]        | [kustomize-guestbook](kustomize-guestbook/)        | The guestbook app as a Kustomize app                                                                                                                                                                                     |
| [example.plugin-kasane][app_plugin_kasane]                    | [plugins/kasane](plugins/kasane)                   | Apps which demonstrate config management plugins usage with [kasane](plugins/kasane/README.md)                                                                                                                           |
| [example.plugin-kustomized-helm][app_plugin_kustomized_helm]  | [plugins/kustomized-helm](plugins/kustomized-helm) | Apps which demonstrate config management plugins usage with a [kustomized helm chart](plugins/kustomized-helm/README.md)                                                                                                 |
| [example.pre-post-sync][app_pre_post_sync]                    | [pre-post-sync](pre-post-sync/)                    | Demonstrates Argo CD PreSync and PostSync hooks                                                                                                                                                                          |
| [example.sock-shop][app_sock_shop]                            | [sock-shop](sock-shop/)                            | A microservices demo app (https://microservices-demo.github.io)                                                                                                                                                          |
| [example.sync-waves][app_sync_waves]                          | [sync-waves](sync-waves/)                          | Demonstrates Argo CD sync waves with hooks                                                                                                                                                                               |

[app_sync_example_apps]: http://10.10.10.222:8002/applications
[app_applicationset]: http://10.10.10.222:8002/applications/argocd/example.applicationset
[app_blue_green]: http://10.10.10.222:8002/applications/argocd/example.blue-green
[app_guestbook]: http://10.10.10.222:8002/applications/argocd/example.guestbook
[app_helm_dependency]: http://10.10.10.222:8002/applications/argocd/example.helm-dependency
[app_helm_guestbook]: http://10.10.10.222:8002/applications/argocd/example.helm-guestbook
[app_helm_hooks]: http://10.10.10.222:8002/applications/argocd/example.helm-hooks
[app_jsonnet_guestbook]: http://10.10.10.222:8002/applications/argocd/example.jsonnet-guestbook
[app_jsonnet_guestbook_tla]: http://10.10.10.222:8002/applications/argocd/example.jsonnet-guestbook-tla
[app_kustomize_guestbook]: http://10.10.10.222:8002/applications/argocd/example.kustomize-guestbook
[app_plugin_kasane]: http://10.10.10.222:8002/applications/argocd/example.plugin-kasane
[app_plugin_kustomized_helm]: http://10.10.10.222:8002/applications/argocd/example.plugin-kustomized-helm
[app_pre_post_sync]: http://10.10.10.222:8002/applications/argocd/example.pre-post-sync
[app_sock_shop]: http://10.10.10.222:8002/applications/argocd/example.sock-shop
[app_sync_waves]: http://10.10.10.222:8002/applications/argocd/example.sync-waves
