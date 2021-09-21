# splunk-otel-jaeger-col

Changes

- Config replacement
  
Edit file `otelAgent.config`
Edit file `values-splunk.yaml`

- Helm Install 
  
Run something like...

`helm install splunk-otel-collector --values values-splunk.yaml -f otelAgent.config splunk-otel-collector-chart/splunk-otel-collector`