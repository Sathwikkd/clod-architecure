# 💰 Sample Budget Setup (Monthly)

This budget-friendly setup is designed for small startups looking to efficiently manage cloud infrastructure while keeping costs low.

| **Component**   | **Provider**         | **Type**        | **Approx Cost** |
|------------------|----------------------|------------------|------------------|
| App Server (4GB, 2vCPU) | Hetzner              | VPS              | $5–$8           |
| DB Server (2GB, 1vCPU)  | Oracle Cloud Free    | Free Tier VPS    | $0              |
| Object Storage          | Wasabi / Backblaze   | 100GB Storage     | $1–$2           |
| DNS & SSL              | Cloudflare           | DNS & HTTPS       | $0              |
| Monitoring             | Netdata / Uptime Kuma| Self-hosted       | $0              |

---

## 📌 Notes
- **Hetzner VPS** is a great low-cost provider with powerful hardware, ideal for backend services.
- **Oracle Cloud Free Tier** offers always-free VMs and managed databases for light workloads.
- **Wasabi/Backblaze B2** are excellent alternatives to AWS S3 for object storage at much lower prices.
- **Cloudflare** offers free SSL, CDN, and DNS management.
- **Monitoring** with self-hosted tools like [Netdata](https://www.netdata.cloud/) or [Uptime Kuma](https://github.com/louislam/uptime-kuma) ensures visibility with zero cost.

---

## ✅ Total Estimated Monthly Cost
**$6–$10/month** for a solid, scalable cloud setup.
