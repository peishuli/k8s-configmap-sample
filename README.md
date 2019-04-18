i# k8s-configmap
This repo contains a sample ASP.NET Core 2.2 web site. The home (index) page displays the logging levels set in appsettings.json.

This sample demonstrates how to using k8s configmap to mount appsettings.json's content during deployemnt (via Helm). It also demonstrates how to force automatically pod restart whenever the config map changes - via an annotation.
