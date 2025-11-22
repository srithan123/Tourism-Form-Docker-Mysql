Sure, Srithan! Here's a professional `README.md` file for your **Tourism Booking Form** project with Docker and MySQL integration:

```markdown
# Tourism Booking Form

A simple **Tourism Booking Form** web application developed using **HTML** for frontend, **MySQL** for database, and **Docker** for containerized deployment.

---

## Features

- User-friendly tourism booking form.
- Stores booking details in a MySQL database.
- Fully containerized using Docker and Docker Compose.
- Easy to run on any system with Docker installed.

---

## Project Structure

```

tourism-booking/
├── frontend/
│   └── index.html
├── backend/
│   └── server.js (or your backend code)
├── docker-compose.yml
└── README.md

````

---

## Prerequisites

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

---

## Running the Project

1. **Start the project using Docker Compose:**
```bash
docker-compose up -d
````

2. **Access MySQL in the terminal:**

```bash
docker exec -it tourism-mysql mysql -u root -p
```

Enter your password (`srithan` by default).

3. **Switch to the project database:**

```sql
USE tourism;
```

4. **View tables in the database:**

```sql
SHOW TABLES;
```

5. **View data in the `bookings` table:**

```sql
SELECT * FROM bookings;
```

6. **Stop and remove containers, networks, and volumes:**

```bash
docker-compose down -v
```

---

## Notes

* Default MySQL username: `root`
* Default MySQL password: `srithan`
* Database name: `tourism`

---

## License

This project is open-source and free to use.


