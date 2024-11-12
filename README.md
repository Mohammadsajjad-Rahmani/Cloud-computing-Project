# Django DRF Docker Project

## مقدمه
این پروژه یک API ساخته شده با استفاده از Django و Django REST Framework (DRF) است که در Docker کانتینر شده است. هدف این پروژه ارائه یک ساختار قابل توسعه و مقیاس‌پذیر برای توسعه‌دهندگان است.

## تکنولوژی‌ها
- **Django**: چارچوب وب پایتون
- **Django REST Framework**: برای ساخت APIهای قدرتمند
- **Docker**: برای کانتینر سازی و مدیریت سرویس‌ها

## نصب و راه‌اندازی

### پیش‌نیازها
- Docker
- Docker Compose

#### نصب Docker
1. بروزرسانی پکیج‌ها:
    ```bash
    sudo apt-get update
    sudo apt-get install -y ca-certificates curl gnupg
    ```
2. افزودن کلید رسمی Docker:
    ```bash
    sudo install -m 0755 -d /etc/apt/keyrings
    curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg
    sudo chmod a+r /etc/apt/keyrings/docker.gpg
    ```
3. اضافه کردن ریپازیتوری Docker:
    ```bash
    echo "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
    ```
4. نصب Docker:
    ```bash
    sudo apt-get update
    sudo apt-get install -y docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
    ```

#### نصب Git
1. نصب Git از طریق APT:
    ```bash
    sudo apt-get install git
    ```
   
# پوشه Screenshots
- تصاویر مربوط به تست ابزار های نصب شده و روند پیشرفت پروژه در این پوشه قرار داده شده 

