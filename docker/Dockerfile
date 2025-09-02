FROM quay.io/jitesoft/nginx:latest as BASE-amd64

ENV PORT="8080"

LABEL konflux.additional-tags="test-tag1, test-tag2"

FROM BASE-{$TARGETARCH}

LABEL foo="bar"
