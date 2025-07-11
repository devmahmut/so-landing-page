# StashOffer Landing Page

A modern, responsive landing page for StashOffer - AI-Powered Market Research Agent.

## Features

- 🚀 Modern and responsive design
- 🌙 Dark/Light mode toggle
- 📱 Mobile-friendly interface
- 🎨 Beautiful UI with Tailwind CSS
- ⚡ Fast loading with optimized assets

## Docker Usage

### Pull and Run

```bash
# Pull the latest image
docker pull devmahmut/so-landing-page:latest

# Run the container
docker run -d -p 8080:80 --name stashoffer-landing devmahmut/so-landing-page:latest
```

### Access the Website

Once the container is running, you can access the website at:
- **Local**: http://localhost:8080
- **Network**: http://your-ip:8080

### Stop and Remove Container

```bash
# Stop the container
docker stop stashoffer-landing

# Remove the container
docker rm stashoffer-landing
```

## Development

### Local Development

1. Clone the repository
2. Open `index.html` in your browser
3. Or use a local server:
   ```bash
   python -m http.server 8000
   # or
   npx serve .
   ```

### Build Docker Image

```bash
# Build the image
docker build -t devmahmut/so-landing-page:latest .

# Push to Docker Hub
docker push devmahmut/so-landing-page:latest
```

## Technologies Used

- HTML5
- CSS3 (Tailwind CSS)
- JavaScript (Alpine.js)
- Docker
- Nginx

## License

This project is proprietary and confidential.

---

**StashOffer** - Transform your vision into reality with our powerful AI UI Kit. 