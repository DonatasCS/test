


# PROVISIONING_DEVICE_ADMIN_SIGNATURE_CHECKSUM

cat app.apk | openssl dgst -sha256 -binary | openssl base64 | tr '+/' '-_' | tr -d '='


# QR

[QR](https://good-qrcode.com/)

