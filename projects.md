[
  {
"id": 1,
"title": "SoundScript — Audio Transcription & Summarization",
"tech": ["React", "Flask", "Gunicorn", "Nginx", "AWS EC2", "Python", "Whisper"],
"preview": "https://soundscript-media.s3.us-east-1.amazonaws.com/ScreenRecording2025-08-22at10.11.34AM-ezgif.com-video-to-gif-converter.gif",
"description": "Uploads audio, transcribes speech to text, and generates concise summaries via a secure HTTPS API.",
"problem": "Turning recordings into readable notes is slow and error‑prone without automation.",
"solution": "A browser frontend uploads audio to a Flask API; the backend performs transcription and returns summaries, all behind Nginx with TLS.",
"results": "End-to-end HTTPS with stable latency for short clips; health checks and CORS configured for production.",
"github": "https://github.com/lokicodess/soundscript-backend",
"demo": "https://soundscript.me",
"architecture": "React app on soundscript.me calls API at api.soundscript.me. Nginx terminates TLS and proxies to Gunicorn on 127.0.0.1:8000 running Flask endpoints (/transcribe, /summarize). Certificates via Certbot.",
"screenshots": ["https://soundscript-media.s3.us-east-1.amazonaws.com/Screenshot+2025-08-22+at+9.48.48%E2%80%AFAM.png","https://soundscript-media.s3.us-east-1.amazonaws.com/Screenshot+2025-08-22+at+9.49.30%E2%80%AFAM.png","https://soundscript-media.s3.us-east-1.amazonaws.com/Screenshot+2025-08-22+at+9.49.37%E2%80%AFAM.png"]
}
]
