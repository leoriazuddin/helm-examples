When Tiller evaluates a chart, it sends all files in templates/ directory to template rendering engine. Then the results of these tempaltes are sent to Kubernetes.

values.yaml contains default values for chart. these can be overridden during helm install or helm upgrade.

Chart.yaml contains description of chart. Can be accessed from within template.

charts/ directory may contain other charts (subcharts).

##Commands

**Commands**
