export HONEYCOMB_API_KEY="I60z1DhnrrdixwFKKexXdE"
gp env HONEYCOMB_API_KEY='I60z1DhnrrdixwFKKexXdE'

export HONEYCOMB_SERVICE_NAME="Cruddur"
gp env HONEYCOMB_SERVICE_NAME="Cruddur"



OTEL_SERVICE_NAME: "${HONEYCOMB_SERVICE_NAME}"
OTEL_EXPORTER_OTLP_ENDPOINT: "https://api.honeycomb.io"
OTEL_EXPORTER_OTLP_HEADERS: "x-honeycomb-team=${HONEYCOMB_API_KEY}"


opentelemetry-api 
opentelemetry-sdk 
opentelemetry-exporter-otlp-proto-http 
opentelemetry-instrumentation-flask 
opentelemetry-instrumentation-requests