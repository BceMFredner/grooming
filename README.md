# 🐾 Бот для грумеров

[🇷🇺 Русский](#-русский) | [🇬🇧 English](#-english)

![Status](https://img.shields.io/badge/status-study_project-blue)
![Platform](https://img.shields.io/badge/platform-Telegram-26A5E4?logo=telegram&logoColor=white)
![Tech](https://img.shields.io/badge/AI-Computer_Vision-orange)
![DB](https://img.shields.io/badge/Redis-in_memory-red)[web:22][web:24][web:28][web:31]

---

## 🇷🇺 Русский

### 📌 Описание проекта

«Бот для грумеров» — это Telegram‑бот и backend‑сервис, который по фотографии питомца определяет животное и рекомендует список услуг по уходу. Проект ориентирован на груминг‑салоны и частных мастеров и помогает автоматизировать первичную консультацию клиента и предварительный расчёт заказа.[web:19][web:21]

Бот принимает фото питомца, передаёт его в ML‑модель компьютерного зрения и на основе результата подбирает перечень процедур (например, мытьё, стрижка, тримминг) с примерным временем выполнения и ориентировочной стоимостью. Сервис может интегрироваться с внутренней ERP‑системой салона для учёта клиентов, очереди и загрузки мастеров.

Проект выполняется как прикладная студенческая работа в области **прикладного** искусственного интеллекта и демонстрирует связку Telegram‑бота, ML‑модуля и быстрой in‑memory БД (Redis) для хранения сессий и данных о запросах клиентов.[web:2][web:3][web:6][web:9]

---

## 🇬🇧 English

### 📌 Project description

“Groomer Bot” is a Telegram bot and backend service that analyzes a pet photo, detects the animal, and recommends a set of grooming services. The project targets grooming salons and independent groomers and aims to automate the initial client consultation and preliminary order estimation.[web:19][web:18]

The bot receives a pet photo, sends it to a computer‑vision ML model, and uses the prediction to select suitable procedures (such as washing, haircut, trimming) with an approximate execution time and price. The service can be integrated with a salon’s internal ERP system to manage clients, queues, and groomer workload.

The project is developed as an applied student work in the field of **applied** artificial intelligence and demonstrates the integration of a Telegram bot, an ML module, and a fast in‑memory database (Redis) for storing user sessions and client requests.[web:2][web:3][web:6][web:9]
