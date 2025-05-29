🧩 Docker ve Kubernetes Proje Özeti
Bu projede, Docker ve Kubernetes teknolojilerini kullanarak basit bir web uygulamasının nasıl container hâline getirileceğini ve Kubernetes üzerinde nasıl çalıştırılacağını öğrendik.
🐳 Docker ile Neler Yaptık?
•	Bir HTML tabanlı "Hello Web" uygulaması oluşturduk.
•	Bu uygulama için Dockerfile yazdık.
•	docker build komutu ile uygulamadan bir Docker imajı oluşturduk.
•	Bu imajı Docker Hub hesabımıza yükledik (docker push).
☸️ Kubernetes ile Neler Yaptık?
•	Uygulamanın Deployment ve Service yapılarını tanımlayan bir YAML dosyası oluşturduk.
•	kubectl apply -f komutu ile bu yapılandırmaları Kubernetes cluster'ımıza uyguladık.
•	Oluşturduğumuz service ile uygulamayı localhost üzerinden erişilebilir hâle getirdik.
🔧 Kullanılan Komutlardan Bazıları:
docker build -t hello-web .
docker tag hello-web rojinyzc21/hello-web
docker push rojinyzc21/hello-web
kubectl apply -f hello-web-deployment.yaml
kubectl get pods
kubectl get services
🎯 Proje Amacı
Bu proje sayesinde:
•	Docker ve Kubernetes kavramlarının gerçek hayatta nasıl bir arada çalıştığını gördük.
•	Mikroservis temelli mimarilerde container yönetimi nasıl yapılır öğrendik.
•	YAML dosyalarının Kubernetes kaynaklarını tanımlamada nasıl kullanıldığını deneyimledik.

