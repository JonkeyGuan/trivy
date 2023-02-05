# trivy image

podman login quay.io

podman build -t quay.io/jonkey/trivy .

podman push quay.io/jonkey/trivy 
