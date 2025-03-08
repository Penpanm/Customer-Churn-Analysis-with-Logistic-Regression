# Customer Churn Analysis with Logistic Regression

Çalışmamız, bir telekomünikasyon firmasının müşteri verileri üzerinde odaklanacak olup, müşteri kaybı (churn) gibi önemli iş kararlarını desteklemek amacıyla veri analizi ve modelleme süreçleri uygulanacaktır. Analiz için gerekli veri seti, firmaların büyük ölçekli verilerini yarışma formatında paylaştığı Kaggle platformundan temin edilmiştir.

**English** 

Our study will focus on customer data from a telecommunications company, applying data analysis and modeling processes to support important business decisions such as customer churn. The dataset required for the analysis has been obtained from the Kaggle platform, where companies share large-scale data in a competition format.

**Veri Seti Kolonları | Dataset Columns** 

-gender: Cinsiyet (Erkek/Kadın) / Gender (Male/Female)
-SeniorCitizen: Yaşlı Vatandaş (1 = Evet, 0 = Hayır) / Senior Citizen (1 = Yes, 0 = No)
-Partner: Evli mi? (Yes = Evet, No = Hayır) / Partner (Yes = Married, No = Not Married)
- Dependents: Bağımlı kişi var mı? (Yes = Evet, No = Hayır) / Dependents (Yes = Has dependents, No = No dependents)
- tenure: Müşteriyle kaç aydır çalışılıyor / Number of months the customer has stayed with the company
- PhoneService: Telefon hizmeti var mı? (Yes/No) / Whether the customer has phone service (Yes/No)
- MultipleLines: Birden fazla telefon hattı var mı? / Whether the customer has multiple lines (Yes/No)
- InternetService: İnternet hizmeti türü (DSL, Fiber optic, Yok) / Type of internet service (DSL, Fiber optic, No)
- OnlineSecurity: Online güvenlik hizmeti var mı? (Yes/No) / Whether the customer has online security service (Yes/No)
- OnlineBackup: Online yedekleme hizmeti var mı? (Yes/No) / Whether the customer has online backup service (Yes/No)
- DeviceProtection: Cihaz koruma hizmeti var mı? (Yes/No) / Whether the customer has device protection service (Yes/No)
- TechSupport: Teknik destek hizmeti var mı? (Yes/No) / Whether the customer has technical support service (Yes/No)
- StreamingTV: TV yayını hizmeti var mı? (Yes/No) / Whether the customer has streaming TV service (Yes/No)
- StreamingMovies: Film yayını hizmeti var mı? (Yes/No) / Whether the customer has streaming movies service (Yes/No)
- Contract: Kontrat tipi (Aylık, 1 Yıllık, 2 Yıllık) / Contract type (Month-to-month, One year, Two year)
- PaperlessBilling: Kağıtsız fatura var mı? (Yes/No) / Whether the customer has paperless billing (Yes/No)
- PaymentMethod: Ödeme yöntemi (Elektronik Çek, Otomatik Transfer, Kredi Kartı) / Payment method (Electronic check, Bank transfer, Credit card)
- MonthlyCharges: Aylık ücret (USD) / Monthly charges in USD
- TotalCharges: Toplam ücret (USD) / Total charges in USD
- Churn: Müşteri kaybı (Yes = Ayrıldı, No = Kalmaya Devam Ediyor) / Customer churn (Yes = Left, No = Remained)
