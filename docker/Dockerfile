FROM harness0.harness.io/oci/docker_artifacts/hhi/harnessos-alpine:1
RUN apk update && apk upgrade --no-cache && apk add -U --no-cache 'ca-certificates>=20261020-r0'

ADD release/linux/amd64/plugin /bin/
ENTRYPOINT ["/bin/plugin"]
