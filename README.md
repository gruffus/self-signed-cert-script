# Устанавливаем 3x-ui панель для VLESS и сертификаты на 10 лет

## 📚 Описание

Этот скрипт автоматически устанавливает:
1. Панель **3X-UI** для управления VPN-протоколами.
2. Самоподписной **SSL-сертификат** сроком на **10 лет**.

## 🛠️ Что будет установлено?
- **OpenSSL**
- **QRencode**
- **3X-UI**

## 🚀 Как использовать?

### 1. Клонирование репозитория
```bash
sudo apt update && sudo apt install -y git curl openssl qrencode systemd && rm -rf ~/self-signed-cert-script && git clone https://github.com/gruffus/self-signed-cert-scrip.git && cd self-signed-cert-script && chmod +x self_signed_cert.sh && sudo ./self_signed_cert.sh
