# Mini Nmap Go

A simple network scanner written in Go to discover hosts and open ports, inspired by Nmap.

## 🔧 Features
- Scan a single IP or IP range
- Scan TCP (specific port range or common ports)
- Results in JSON or console output
- User-friendly CLI with Cobra

## 🚀 Usage
```bash
go run cmd/main.go scan --ip 192.168.1.1 --ports 22,80,443
```

## 🧱 Stack
- Go + Cobra
- Docker
- Jenkins (CI/CD)
- GitHub Actions (optional)

## 📦 Installation (Docker)
```bash
docker build -t mini-nmap .
docker run --rm mini-nmap scan --ip 192.168.1.1
```

## ✅ Roadmap
- [ ] Basic IP scan
- [ ] Concurrent scanning
- [ ] HTML output export
- [ ] Banner detection

## 📂 Project Structure
```
/cmd
  main.go
/scanner
  scanner.go
/docker
  Dockerfile
/jenkins
  Jenkin
```

## 🤝 Contributing
Pull requests are
