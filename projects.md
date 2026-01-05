[
{
    "id": 2,
    "title": "clck.dev — URL Shortener",
    "tech": [
      "React",
      "Go (Golang)",
      "AWS EC2",
      "AWS RDS (MySQL)",
      "Redis",
      "Docker",
      "K3s",
      "Nginx",
      "Traefik",
      "Prometheus",
      "Grafana"
    ],
    "preview": "https://lokicodess-url-shortner.s3.ap-south-1.amazonaws.com/Screen+Recording+2026-01-05+at+2.47.19+PM.gif",
    "description": "A scalable URL shortening platform that converts long URLs into short links with fast redirection and production-grade reliability.",
    "problem": "Long URLs are inconvenient to share and track, and naïve URL shorteners fail under high read traffic or partial failures.",
    "solution": "A stateless Go backend generates unique short codes, stores mappings in MySQL, caches hot paths in Redis, and serves redirects with low latency behind a reverse proxy and ingress controller.",
    "results": "Sub-millisecond redirects for cached URLs, horizontal scalability via Kubernetes, HTTPS termination, rate limiting, and real-time observability with Prometheus and Grafana.",
    "github": "https://github.com/lokicodess/url-shortner",
    "demo": "https://clck.dev",
    "architecture": "Route53 routes traffic to a Traefik Ingress on a K3s cluster. Traefik forwards frontend requests to the React app (clck.dev) and API requests to the Go service (api.clck.dev). The Go API is stateless, backed by MySQL (RDS) for persistence and Redis for caching. Nginx handles internal reverse proxying, while Prometheus scrapes metrics and Grafana visualizes system health.",
    "screenshots": [
      "https://lokicodess-url-shortner.s3.ap-south-1.amazonaws.com/Screenshot+2026-01-05+at+14-44-51+Clck+%E2%80%A2+URL+Shortener.png"
    ]
  }
]
