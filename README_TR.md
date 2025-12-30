# İK Analitiği – Çalışan Ayrılma (Attrition) ve Performans Tahmini
## Veri Madenciliği Projesi

## 📌 Proje Tanımı
Bu repository, **Veri Madenciliği dersi kapsamında** geliştirilen bir projeyi içermektedir.  
Projenin temel amacı:

- **Çalışanların işten ayrılıp ayrılmayacağının tahmin edilmesi (Attrition Prediction)**
- **Çalışan performanslarının analiz edilmesi**
- **Regrettable Attrition (yüksek performanslı çalışanların ayrılması)** durumlarının incelenmesi

Çalışma, ham veri incelemesinden başlayarak özellik çıkarımı, modelleme, hiperparametre optimizasyonu ve nihai değerlendirmeye kadar **iteratif ve analitik bir süreç** izlemektedir.

---

## 🎯 Proje Amaçları
- İnsan kaynakları verilerinin analizi
- Çalışan davranışlarını etkileyen faktörlerin belirlenmesi
- Makine öğrenmesi modelleri ile ayrılma tahmini yapılması
- Performans ve ayrılma ilişkilerinin incelenmesi
- Akademik olarak tekrar üretilebilir ve açıklanabilir sonuçlar elde edilmesi

---

## 🧠 Kullanılan Yöntem
Proje aşağıdaki veri madenciliği adımlarını izlemektedir:

1. Ham veri yükleme ve doğrulama
2. Keşifsel Veri Analizi (EDA)
3. Veri temizleme ve ön işleme
4. Özellik mühendisliği
5. Temel (baseline) makine öğrenmesi modelleri
6. İteratif model optimizasyonu
7. Nihai değerlendirme ve raporlama

Her adım ayrı Jupyter Notebook’lar ile yapılandırılmıştır.

---

## 📂 Notebook Açıklamaları

### 🔹 Ham Veri & EDA
- `HR01_00_raw_sanity_check_v01.ipynb`  
  Ham veri kontrolü ve temel doğrulamalar.

- `HR01_00_raw_load_performance_attrition_v01.ipynb`  
  Performans ve ayrılma verilerinin yüklenmesi.

- `HR01_01_eda_quick_overview_v01.ipynb`  
  Genel keşifsel veri analizi.

- `HR01_01_eda_attrition_patterns_alt_v01.ipynb`  
  Ayrılma (attrition) odaklı detaylı EDA.

---

### 🔹 Temizleme & Özellik Mühendisliği
- `HR01_02_cleaning_preprocess_v01.ipynb`  
  Veri temizleme ve kodlama işlemleri.

- `HR01_03_features_pipeline_v01.ipynb`  
  Özellik çıkarımı ve dönüşümler.

- `HR02_02_features_regrettable_recipes_v01.ipynb`  
  Regrettable attrition için özel olarak tasarlanmış özellikler.

---

### 🔹 Modelleme & Değerlendirme
- ⭐ `HR01_04_modeling_course_submission_v01.ipynb`  
  **Ders kapsamında hocaya sunulan ana notebook.**  
  Temel modeller ve değerlendirme sonuçlarını içerir.

- `HR02_04_modeling_regrettable_full_experiments_v01.ipynb`  
  Regrettable attrition için genişletilmiş model denemeleri.

---

### 🔹 Optimizasyon & Nihai Raporlar
- `HR01_05_tuning_iterative_model_search_v01.ipynb`  
  Hiperparametre optimizasyonu ve model karşılaştırmaları.

- `HR01_07_report_final_pipeline_v01.ipynb`  
  Baştan sona nihai analiz ve sonuçlar.

- `HR01_07_report_final_pipeline_backup_v01.ipynb`  
  Nihai pipeline yedeği.

- `HR01_07_report_final_sanity_checks_v01.ipynb`  
  Son kontroller ve doğrulamalar.

- `HR02_07_report_regrettable_clean_results_v01.ipynb`  
  Regrettable attrition için temizlenmiş nihai sonuçlar.

---

## 🧪 Kullanılan Modeller ve Teknikler
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- Veri Ölçekleme ve Kodlama  
- Çapraz Doğrulama (Cross-Validation)  
- Değerlendirme Metrikleri: Accuracy, Precision, Recall, F1-Score, Confusion Matrix

---

## 🏁 Notlar
- Notebook’lar **kronolojik ve mantıksal sırayla** düzenlenmiştir.
- Proje, akademik değerlendirme için **şeffaf ve tekrar üretilebilir** yapıdadır.
- Ana teslim dosyası özellikle belirtilmiştir.

---

## 👩‍💻 Hazırlayan
**Arzu Selda Avcı**  
Bilgisayar Mühendisliği – Veri Madenciliği Projesi
