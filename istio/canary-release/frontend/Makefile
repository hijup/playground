build:
	docker build . -t playground-istio-frontend
run:
	docker run -p 8080:8080 -it --rm playground-istio-frontend
deploy:
	kubectl apply -f manifests/k8s.yaml
