# predicting-campaign
Proyek ini bertujuan untuk memprediksi efektivitas kampanye pemasaran berdasarkan data historis kampanye.Efektivitas ditentukan dari metrik ROI (Return on Investment), dengan kriteria:
ROI ≥ 1.5 → Efisien
ROI < 1.5 → Tidak Efisien

🎯 Tujuan
Membangun model klasifikasi untuk memprediksi kampanye yang efisien.

Membantu tim marketing dalam pengambilan keputusan berdasarkan data kampanye historis.

📁 Dataset Overview
Jumlah data: 10.000 baris, 17 kolom

Beberapa fitur penting:

Budget, Clicks, Conversions, Revenue, Discount, Units_Sold

Subscription_Tier, Subscription_Length, Customer_Refund, Bundle_Price

Label target: ROI (digunakan untuk membuat label klasifikasi)

🧠 Metode & Model
Model yang digunakan:

Logistic Regression

Random Forest Classifier

Proses meliputi:

Preprocessing data numerik dan kategorikal

One-Hot Encoding untuk fitur seperti Subscription_Tier dan Keywords

Balancing data jika diperlukan (misalnya menggunakan SMOTE)

Evaluasi menggunakan:
1. Accuracy
2. Precision
3. Recall
4. F1-Score
5. Confusion Matrix

