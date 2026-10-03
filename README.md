# Bank Telemarketing Potential Leads Prediction
Sebuah Project Machine Learning yang bertujuan untuk membuat model algoritma yang dapat memprediksi potential leads agar bisa digunakan oleh tim telemarketing sebuah bank yang ingin meningkatkan pendaftaran deposito berjangka

## Repository Outline
```
1. README.md - Penjelasan gambaran umum project
2. notebook.ipynb - Notebook yang berisi EDA, Feature Engineering, Training, Evaluasi, dan Hyperparameter Tuning Model.
3. notebook_inf.ipynb - Notebook yang berisi inference model terbaik.
4. bank-full.csv - Dataset yang digunakan untuk training model.
5. utils.py - Berisi function untuk melakukan handling cardinality sekaligus menambah indikator pada kolom pdays untuk mengubah nilai -1
```

## Problem Background
Pelaksanaan direct marketing campaign yang dilakukan oleh bank seringkali memakan banyak biaya dan effort tim marketing dan telemarketing. Hal ini biasa disebabkan oleh kurangnya pre-screening sebelum campaign dieksekusi sehingga banyak leads atau nasabah yang sebetulnya tidak tertarik juga menjadi target dalam campaign tersebut.

Maka dari itu model prediksi ini dibuat untuk membantu tim marketing dalam menentukan profil nasabah mana yang bisa dihubungi lebih lanjut untuk ditawarkan produk deposit berjangka. Project ini bertujuan untuk mencari model algoritma classification terbaik dengan melakukan percobaan ke berbagai jenis algoritma seperti KNN, SVM, Decision Tree, Random Forest dan XGBoost.


## Project Output
Output dari project ini berupa model algortima terbaik yang didapat dari proses training dan hyperparameter tuning, slide presentation, serta sebuah app website yang berisikan hasil dari EDA serta inferencing interactive yang berjalan berdasarkan hasil model terbaik.

- [Streamlit App Deployment for Prediction](https://bank-marketing-prediction-noveliq.streamlit.app/)
- [Slide Presentation](https://canva.link/a5lovf0zgasxke9)

## Data
Model di-training menggunakan dataset dari penelitian Sérgio Moro, P. Cortez, dan P. Rita pada tahun 2014 yang diunduh dari UCI Machine Learning Repository. Dataset ini memiliki total 45.211 baris dan 17 kolom.

## Method
Metode yang digunakan dalam project ini adalah supervised learning dengan berbagai model classifier seperti KNN, SVM, Decision Tree, Random Forest, dan XGBoost

## Stacks
pandas - for data processing and analyzing
numpy - for data processing and analyzing
matplotlib - for data visualization
pickle - for saving and loading model  
scipy - for statictical analysis
sklearn - for feature engineering and algorithm learning
feature_engine - for feature engineering    
xgboost - for algorithm learning

## Reference
- [UCI Machine Learning Repository - Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing)
- [Direct Marketing](https://www.bee.id/blog/direct-marketing/)
- [XGBoost Documentation](https://xgboost.readthedocs.io/en/stable/)
