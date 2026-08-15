# Real-Time AI Video Analytics & Surveillance Dashboard

A high-throughput video analytics dashboard for real-time object detection, alert triggering, and historical log querying.

## 🚀 Key Features
- **Real-Time Detection:** Integrates YOLOv8 object detection model with OpenCV for video stream processing.
- **Low-Latency Streaming:** WebSocket server built with Node.js/Express streaming metadata to frontend under 100ms.
- **Dashboard:** Interactive analytics frontend built with Next.js and Chart.js.
- **Historical Logging:** Indexed PostgreSQL database for fast query execution over 500k+ event records.

## 🛠️ Tech Stack
`Next.js` `Node.js` `WebSockets` `YOLOv8` `OpenCV` `PostgreSQL` `Tailwind CSS`

## ⚙️ Quick Start
```bash
# Clone repository
git clone [https://github.com/DuyWebdev/ai-surveillance.git](https://github.com/DuyWebdev/ai-surveillance.git)

# Install dependencies and start server
npm install
npm run dev
