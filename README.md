# py-theatre-service-api
An API for the theatre in your town. The idea is to allow theatregoers to book tickets online and choose their preferred seats without having to go to the theatre in person

## DB Structure
![DB Structure](https://github.com/shafran-andriy/py-theatre-service-api/blob/main/docs/models.svg)

## Features

- 🔐 JWT authentication
- 📧 Email authentication
- 🛠 Admin panel available at `/admin/`
- 📄 API documentation available at `/api/doc/swagger/`

### Core functionality

- 🎭 Manage plays (with genres and actors)
- 🏛 Manage theatre halls
- 🎟 Manage reservations and tickets
- 🕒 Create and manage performances (show times)
- 🔍 Filter plays and performances

## Load test data

Use the following command to load prepared data for testing and debugging:

```bash
python manage.py loaddata cinema_service_db_data.json
```

## Test credentials

Use the following credentials to access the system:

- **Email:** admin@test.test  
- **Password:** Qazwsx1!

## Pages images:

### Actor List
![Actor List](https://github.com/shafran-andriy/py-theatre-service-api/blob/main/photos_of_the_api/ActorList.png)

### Performance List
![Performance List](https://github.com/shafran-andriy/py-theatre-service-api/blob/main/photos_of_the_api/PerformanceList.png)

### Performance Instance
![Performance Instance](https://github.com/shafran-andriy/py-theatre-service-api/blob/main/photos_of_the_api/Performance_Instance.png)

### Genre List
![Genre List](https://github.com/shafran-andriy/py-theatre-service-api/blob/main/photos_of_the_api/GenreList.png)

### Theatre Hall List
![Theatre Hall List](https://github.com/shafran-andriy/py-theatre-service-api/blob/main/photos_of_the_api/TheatreHallList.png)
