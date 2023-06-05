# Prompt Manifest 

| NAME                    | PROMPT                | DESCRIPTION                                   | EXAMPLE                                                                         |
|-------------------------|-----------------------|-----------------------------------------------|---------------------------------------------------------------------------------|
| app.yaml                | App YAML manifest     | Defines app deployment                        | [app.yaml](https://github.com/ivanmartovytskyi/prompt-demo/blob/master/yaml/app.yaml)                                |
| app-livenessProbe.yaml  | App Liveness probe    | Liveness probe for the Pod                    | [app-livenessProbe.yaml](https://github.com/ivanmartovytskyi/prompt-demo/blob/master/yaml/app-livenessProbe.yaml)  |
| app-readinessProbe.yaml | App Readiness probe   | Readiness probe for the Pod                   | [app-readinessProbe.yaml](https://github.com/ivanmartovytskyi/prompt-demo/blob/master/yaml/app-readinessProbe.yaml) |
| app-volumeMounts.yaml   | App Volume mounts     | Defines volume mounts for the Pod             | [app-volumeMounts.yaml](https://github.com/ivanmartovytskyi/prompt-demo/blob/master/yaml/app-volumeMounts.yaml)   |
| app-cronjob.yaml        | App Cronjob           | Schedules jobs on a cron-like schedule        | [app-cronjob.yaml](https://github.com/ivanmartovytskyi/prompt-demo/blob/master/yaml/app-cronjob.yaml)               |
| app-job.yaml            | App job manifest      | Runs pod with job                             | [app-job.yaml](https://github.com/ivanmartovytskyi/prompt-demo/blob/master/yaml/app-job.yaml)                        |
| app-multicontainer.yaml | multicontainer pod    | Pod with multiple containers                  | [app-multicontainer.yaml](https://github.com/ivanmartovytskyi/prompt-demo/blob/master/yaml/app-multicontainer.yaml) |
| app-resources.yaml      | pod resources         | Configures pod's resources                    | [app-resources.yaml](https://github.com/ivanmartovytskyi/prompt-demo/blob/master/yaml/app-resources.yaml)             |
| app-secret-env.yaml     | app secret env        | Secret env value management                   | [app-secret-env.yaml](https://github.com/ivanmartovytskyi/prompt-demo/blob/master/yaml/app-secret-env.yaml)|
