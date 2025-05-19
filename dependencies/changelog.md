# changelog


1.0.3
add reloader annotation

1.0.4
fix template error

1.0.5
add template for alb-service-ingress

1.0.6
move alb ssl redirect rule to 1st rule

1.0.7
add back empty old template for external reference compatible

1.0.8
add configmap external for external reference

1.0.9
- refactor healthcheck part, healthcheck part add optional timeout
- add lifecycle part with default preStop
- remove replicacount if not specific, workaround helm2/helm3 bug/feature
- add default rolling-update part with unavailable 0

1.0.10
- fix prestop sleep time

1.0.11
- update default imagePullPolicy: to "IfNotPresent"
