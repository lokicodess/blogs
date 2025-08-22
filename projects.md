[
{
    "id": 1,
    "title": "Real-Time Sentiment Dashboard",
    "tech": ["MERN", "NLP", "AWS"],
    "preview": "https://media.giphy.com/media/3o7aD2saalBwwftBIY/giphy.gif",
    "description": "Monitors Twitter for sentiment analysis via NLP.",
    "problem": "No easy way to visualize public opinion in real time.",
    "solution": "Uses Node.js, React and NLP models for live updates.",
    "results": "Analyzed 10K tweets/day with 95% accuracy.",
    "github": "https://github.com/yourusername/sentiment-dashboard",
    "demo": "#",
    "architecture": "MERN stack app with AWS for hosting and data storage.",
    "screenshots": ["https://placehold.co/400x200"]
  },
  {
"id": 2,
"title": "SoundScript — Audio Transcription & Summarization",
"tech": ["React", "Flask", "Gunicorn", "Nginx", "AWS EC2", "Python", "Whisper"],
"preview": "https://streamable.com/db7qhp?src=player-page-share",
"description": "Uploads audio, transcribes speech to text, and generates concise summaries via a secure HTTPS API.",
"problem": "Turning recordings into readable notes is slow and error‑prone without automation.",
"solution": "A browser frontend uploads audio to a Flask API; the backend performs transcription and returns summaries, all behind Nginx with TLS.",
"results": "End-to-end HTTPS with stable latency for short clips; health checks and CORS configured for production.",
"github": "https://github.com/yourusername/soundscript",
"demo": "https://soundscript.me",
"architecture": "React app on soundscript.me calls API at api.soundscript.me. Nginx terminates TLS and proxies to Gunicorn on 127.0.0.1:8000 running Flask endpoints (/transcribe, /summarize). Certificates via Certbot.",
"screenshots": ["https://soundscript-media.s3.us-east-1.amazonaws.com/Screenshot+2025-08-22+at+9.48.48%E2%80%AFAM.png","https://soundscript-media.s3.us-east-1.amazonaws.com/Screenshot+2025-08-22+at+9.49.30%E2%80%AFAM.png","https://soundscript-media.s3.us-east-1.amazonaws.com/Screenshot+2025-08-22+at+9.49.37%E2%80%AFAM.png"]
}
]
