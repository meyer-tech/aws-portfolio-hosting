# Portfolio-Website Hosting mit AWS (Phase 1)

In diesem Projekt habe ich meine persönliche Portfolio-Website komplett cloud-basiert aufgesetzt – unter Einsatz mehrerer AWS-Services. Ziel war es, ein professionelles, skalierbares und sicheres Hosting im Free Tier zu realisieren.

---

## Verwendete AWS-Services

- **Amazon S3** – für statisches Website-Hosting  
- **Amazon CloudFront** – als globales CDN mit HTTPS  
- **AWS Certificate Manager (ACM)** – für kostenloses SSL-Zertifikat  
- **Amazon Route 53** – zur Domain-Verwaltung & DNS-Routing  
- **Custom Domain** – `carstenmeyer.dev`

---

## Live-Demo

**[carstenmeyer.dev](https://carstenmeyer.dev)**  
→ Öffentliche Portfolio-Website mit SSL & CDN

---

## Projektstruktur

/
├── index.html
├── style.css
├── images/
├── files/
├── README.md
├── mixitup.min.js
├── script.js

---

## Ziel

- Aufbau eines cloud-nativen Portfolios
- Verständnis zentraler AWS-Services im Zusammenspiel
- Vorbereitung auf DevOps & Cloud Engineer Positionen

---

## Was ich gelernt habe

- AWS S3 als statischer Webhost
- Public Access über Bucket Policy
- HTTPS mit ACM & CloudFront
- DNS-Management mit Route 53
- Domains verbinden & umleiten (`www → root`)

---

## Nächster Schritt – Phase 2

In Phase 2 werde ich:
- Die Website auf einer **EC2-Instanz mit Nginx** hosten
- Linux-Basics (z. B. SSH, Dateiverwaltung, Webserver)
- Infrastruktur mit Skripten provisionieren (ggf. Terraform)
- Optional: einfache Python-App als Backend ergänzen