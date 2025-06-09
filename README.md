# 🎥 Frigate NVR – Redacted Configuration Example

This repository includes a redacted and documented version of a working Frigate configuration optimized for:

- Dual EdgeTPUs (PCIe Coral)
- NVIDIA GPU decoding
- go2rtc stream management
- Audio-capable cameras (Unifi, Sercomm)

## 🔧 What This Is

A sanitized snapshot of a high-performance Frigate deployment. You can use this as a reference to build or tune your own configuration.

## ⚠️ Redaction Notes

- All usernames, passwords, RTSP tokens, and IP addresses have been replaced with placeholders.
- Replace `CAMERA_IP`, `UNIFI_NVR_IP`, `STREAM_TOKEN_X`, `YOUR_MQTT_USER`, etc., with your actual credentials.

## 📘 How to Use

1. Install [go2rtc](https://github.com/AlexxIT/go2rtc) and configure your camera streams.
2. Copy this config into your `frigate.yml` file.
3. Update all placeholder values with your real configuration.
4. Use Home Assistant or MQTT to integrate Frigate with your smart home system.

## 🧠 Bonus Tips

- Use camera groups to organize Birdseye views.
- Use stream roles (`detect`, `record`) for performance optimization.
- Mask areas of motion or object detection to reduce false positives.

---
