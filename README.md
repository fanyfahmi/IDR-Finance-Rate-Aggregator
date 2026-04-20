# IDR-Finance-Rate-Aggregator
This project is a Spring Boot-based REST API that aggregates exchange rate data from the Frankfurter API, specifically focusing on Indonesian Rupiah (IDR). It demonstrates advanced Spring concepts, clean code principles, and the use of architectural design patterns.

---------------------------------------------------------
# SETUP/RUN INSTRUCTION :

1. Clone Repository

-> git clone https://github.com/fanyfahmi/idr-aggregator.git
-> cd IDR-Finance-Rate-Aggregator
-> git pull origin main

2. Build Aplikasi

-> ./mvnw clean install

3. start unit test

-> ./mvnw test

4. start aplikasi 

-> ./mvnw spring-boot:run

aplikasi berjalan di http://localhost:8080

----------------------------------------------------------

# ENDPOINT USAGE :

1. Latest Rates IDR -> http://localhost:8080/api/finance/data/latest_idr_rates

2. Historical IDR to USD -> http://localhost:8080/api/finance/data/supported_currencies

3. Supported Currencies -> http://localhost:8080/api/finance/data/supported_currencies

-----------------------------------------------------------

# PERSONALIZATION NOTE :

GitHub Username: fanyfahmi

Spread Factor: 0.00947

(Dihitung berdasarkan: Jumlah ASCII "fanyfahmi" (947) % 1000 / 100000.0)

