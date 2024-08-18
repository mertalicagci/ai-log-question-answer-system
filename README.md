ai-log-question-answer-system

Trafik Logları AI Soru-Cevap Sistemi

Proje Açıklaması

Bu proje, web trafik günlüklerini kullanarak AI tabanlı bir soru-cevap sisteminin geliştirilmesini içerir. Sistem, verilen web trafik günlüklerine dayalı olarak soruları yanıtlamak için bir Retrieval-Augmented Generation (RAG) modelini kullanır. Proje, veri hazırlığı ve ön işleme, RAG model kurulumunu, sistem entegrasyonunu ve testini içerir.

Proje Adımları
Veri Hazırlığı ve Ön İşleme

Web trafik günlüklerini analiz edin ve temizleyin.
Veri çerçevesi oluşturun ve TF-IDF vektörizasyonu uygulayın.
RAG Modeli Kurulumu

FAISS ile vektörleme yapın.
T5 modelini kullanarak yanıt üretimi gerçekleştirin.
Sistem Entegrasyonu ve Testi

Kodunuzu test edin ve performans değerlendirmesi yapın.
Performans Değerlendirmesi

Yanıt sürelerini ve doğruluğunu analiz edin.
Kurulum
Projeyi çalıştırmak için aşağıdaki adımları izleyin:

Gerekli Kütüphaneleri Kurma

Python ve gerekli kütüphaneleri kurmak için aşağıdaki komutları kullanın:

pip install pandas scikit-learn faiss-cpu numpy transformers
Kodunuzu Çalıştırma

Kodunuzu çalıştırmak için aşağıdaki adımları izleyin:


python main.py
Kod Yapısı
data_preparation.py: Veri hazırlığı ve ön işleme işlemleri.
rag_model.py: RAG modelinin kurulum ve testi.
utils.py: Yardımcı işlevler ve veri işlemleri.
main.py: Projenin ana çalışma dosyası.
Kullanım
Proje, web trafik günlükleri üzerinden çeşitli soruları yanıtlamak için kullanılabilir. Örnek bir soru ve yanıt işlemi aşağıdaki gibidir:


# Kod
question = "Which IP address accessed /login?"
answer = get_answer(question)
print(answer)
Testler
Projede yer alan testler, modelin performansını ve yanıt doğruluğunu değerlendirmek için yapılmıştır. Testler hakkında daha fazla bilgiye tests/ dizininde bulunan dosyalardan ulaşabilirsiniz.

İletişim
Proje ile ilgili sorularınız veya geri bildirimleriniz için cagcimertali@gmail.com adresine ulaşabilirsiniz.
