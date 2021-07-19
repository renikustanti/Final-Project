Build image 

- Pindah ke working direktori digitalskola_de_final-masster

- docker-compose -f docker-compose.yaml build

Start Container

Untuk running containers, Anda bisa jalankan command berikut

- docker-compose -f docker-compose.yaml up -d

Cek Container log

- docker-compose -f docker-compose.yaml logs 


### Access the containers or apps that were built

Airflow: http://localhost:8080

Postgres - Database Airflow:
* Server: localhost:5432
* Database: airflow
* User: airflow
* Password: airflow

Mohon maaf tugas saya belum selesai, laptop saya ngecrash kak


