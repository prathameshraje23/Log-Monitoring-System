# Log-Monitoring-System

Start Monitoring by following below steps:

Helm charts for java application, fluentd and elastic-kibana are hosted publically using GitHub pages

Add helm repo 
->
helm repo add <repo-name> https://prathameshraje23.github.io/Log-Monitoring-System/helm/charts

Install helm charts
->

For Java Application
->
helm install <chart-name> <repo-name>/java-app

For fluentd log collector
->
helm install <chart-name> <repo-name>/fluentd

For elastic and kibana
->
helm install <chart-name> <repo-name>/ek
