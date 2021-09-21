# splunk-otel-jaeger-col

*note - this chart uses a custom build of the OTEL Collector located at: davepiskai/splunk-otel-jaeger-col*

Changes

- Config replacement
  


Edit variables in file `values-splunk.yaml`

- Helm Install 
  
Install the chart including the values file (`values-splunk.yaml`) and `otelAgent.config`

`helm install splunk-otel-collector --values values-splunk.yaml -f otelAgent.config splunk-otel-collector-chart/splunk-otel-collector`