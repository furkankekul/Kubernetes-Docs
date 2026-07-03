<div align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSBgrQraS2PCTT-czQ9PGzLZNEoog0ClTL5LXihrxrXqyuCX8CZgQS4pVHa&s=10" alt="Kubernetes Logo" width="200">
  
  # Kubernetes-Docs
  
  [![CNCF Graduated](https://img.shields.io/badge/CNCF-Graduated-blue.svg)](https://cncf.io)
  [![Language](https://img.shields.io/badge/Language-Turkish-red.svg)](#)
</div>

---

### 📖 Hakkında

Kubernetes, Google tarafından 6 Haziran 2014’te duyuruldu. Proje, Google çalışanları
Joe Beda, Brendan Burns ve Craig McLuckie tarafından tasarlandı ve oluşturuldu. 1.0
versiyonunu 21 Temmuz 2015’te yayınladı. Google, Cloud Native Computing Foundation
(CNCF) oluşturmak için Linux Foundation ile çalıştı ve Kubernetes’i başlangıç teknolojisi
olarak sundu

## 📌 İçindekiler

* **1. Kubernetes Nedir?**
* **2. Neden Kubernetes’e İhtiyacınız Var?**
* **3. Kubernetes’in Tarihsel Gelişim Süreci**
    * 3.1. Geleneksel Dağıtım Dönemi (Traditional Deployment)
    * 3.2. Sanallaştırılmış Dağıtım Dönemi (Virtualized Deployment)
    * 3.3. Konteyner Dağıtım Dönemi (Container Deployment)
* **4. Kubernetes Komponentleri**
    * 4.1. Temel Bileşenler
      * 4.1.1. Control Plane (Kontrol Düzlemi - Master Node) Component
      * 4.1.2. Node (Düğüm - Worker Node)
      * 4.1.3. Addons (Eklentiler)
* **5. Kubernetes Küme Mimarisi**
    * 5.1. Control Plane (Kontrol Düzlemi - Master Node) Component
      * 5.1.1. kub-apiserver
      * 5.1.2. etcd
      * 5.1.3. kube-scheduler
      * 5.1.4. kube-controller-manager
      * 5.1.5. cloud-controller-manager
    * 5.2.  Node (İşçi Düğüm- Worker Node)
      * 5.2.1. kubelet
      * 5.2.2. kube-proxy
      * 5.2.3. container runtime
  * **6. Konteynerler (Containers)**
      * 6.1. Konteyner İmajları (Container İmages)
      * 6.2. Konteyner Çalışma Zamanı (Container Runtime)
  * **7. İş Yükleri (Workloads)**
      * 7.1. Pods
        * 7.1.1. Pod Nedir?
      * 7.2. Deployment
      * 7.3. Services
        * 7.3.1. Kubernetes'te Servisler
        * 7.3.2. Servis Türleri
      * 7.4. Secret
      * 7.5. ConfigMap
      * 7.6. DeamonSet
      * 7.7. Volume
        * 7.7.1. Volume'lerin Önemi
        * 7.7.2. Volume'ler Nasıl Çalışır
      * 7.8. Persistent Volume
        * 7.8.1. Bir Volume ve Claim'in Yaşam Döngüsü
          * Provisioning (Kaynak Sağlama)
          * Binding (Bağlama)
          * Using (Kullanım)
          * Kullanımdaki Depolama Nesnesi Koruması
          * Recaliming (Geri Alma)
            * Retain (Tutmak)
            * Delete (Silmek) 
          * PersistentVolume Rezerv Etme
          * Erişim Modları
          * Selector (Seçici)
          * Class (Sınıf)
      * 7.9. Storage Classes (Depolama Sınıfları)
        * 7.9.1. StorageClass Objeleri
        * 7.9.2. Default StorageClass
        * 7.9.3. Provisioner (Sağlayıcı)
        * 7.9.4. Reclaim Policy (Geri alma politikası)
        * 7.9.5. Volume Expansion (Birim Genişletme)
        * 7.9.6. Mount Options (Bağlama Seçenekleri)
        * 7.9.7. Volume Binding Mode (Birim Bağlama Modu)
        * 7.9.8. Parameters (Parametreler)
  * **Liveness Probe**
  * **Readiness Probe**
  * **Resource Limits**
  * **Node Affinity**
  * **Pod Affinity**    



