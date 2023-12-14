
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



REACT_AWS_PROJECT_REGION=
REACT_APP_AWS_COGNITO_REGION=
REACT_APP_AWS_USER_POOLS_ID=us-east-1_5qTPa06DX
REACT_APP_CLIENT_ID=48gjkqr1iv36skj5b6d1t3pdb5