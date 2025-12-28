# 🚀 Instagram Reels Automation Dataset (2025 Edition)

A massive, curated collection of **2,500+ High-Retention Video Assets** designed for:
- 🤖 Content Automation Bots
- 🧠 AI Video Generation Models
- 📱 Faceless YouTube/Instagram Channels
- 🎥 Motion Graphics & Commercial Editing

## 📂 Dataset Structure
The dataset is organized into labeled directories for easy programmatic access:

| Category | Count | Resolution | Format |
| :--- | :--- | :--- | :--- |
| **Luxury / Old Money** | 500+ | 4K / 1080p | .mp4 |
| **Dark Aesthetic / Night** | 400+ | 4K / 1080p | .mp4 |
| **Motion Graphics (Loops)** | 1,500+ | 4K | .mp4 |
| **Sigma / Motivation** | 300+ | 1080p | .mp4 |
| **Nature / Soft Life** | 300+ | 4K | .mp4 |

> **License:** Royalty-Free / Commercial Use

## ⚡ Why Use This Dataset?
1.  **Clean Metadata:** Files are named specifically for easy script parsing.
2.  **No Faces:** Optimized for "Faceless" content automation to avoid biometric flagging.
3.  **High Bitrate:** 90% of files are 60fps / 4K quality.

## 📥 How to Download
Due to GitHub's file size limits (100MB), the full dataset is hosted on high-speed private cloud storage (Google Drive).

### 🔓 Get Instant Access
To prevent bot abuse, access to the full repository is gated.

**[👉 Click Here to Get the Access Key (Instant WhatsApp)](YOUR_WHATSAPP_LINK_HERE)**

*Price: ₹159 ($2 USD) for Lifetime Access & Updates.*

## 🛠 Usage Example (Python)
Once you have the dataset, you can use it with `moviepy` for mass automation:

```python
import os
import random
from moviepy.editor import VideoFileClip

# Point this to the downloaded folder
dataset_path = "./Ultimate_Dataset/Luxury"
video_files = [f for f in os.listdir(dataset_path) if f.endswith('.mp4')]

# Select random asset
clip = VideoFileClip(os.path.join(dataset_path, random.choice(video_files)))
print(f"Loaded asset: {clip.duration} seconds")
