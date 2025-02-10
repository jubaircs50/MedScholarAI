# MedScholarAI

/medscholar_ai/
│── backend/
│   │── clinical_engine.py        # মূল AI প্রসেসিং
│   │── vision_diagnosis.py       # মেডিকেল ইমেজ বিশ্লেষণ
│   │── speech_processor.py       # ভয়েস রিকগনিশন ও সিন্থেসিস
│   │── api.py                    # FastAPI দিয়ে Backend সার্ভার  
│   └── models/                    # প্রি-ট্রেইনড মডেলের ওজন
│
│── frontend/
│   │── app.py                    # Gradio UI (Frontend)
│   │── assets/                    # UI ইমেজ ও অডিও ফাইল
│   └── static/                    # CSS ও JavaScript  
│
│── clinical_config.yaml           # মেডিকেল মডেলের কনফিগারেশন  
│── requirements.txt                # নির্দিষ্ট প্যাকেজ লিস্ট
└── README.md                       # প্রজেক্ট ডকুমেন্টেশন
