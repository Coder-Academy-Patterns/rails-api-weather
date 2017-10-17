## Getting Started

Sign up to an account on https://openweathermap.org/

Create a **.env** file in the project root with the following keys set:
```
OPEN_WEATHER_MAP_API_KEY =
```

## Models

### City
- name
- country_code


## Architecture

### Models
- Store data in database
- Process data

### Views
- Present data

### Helpers
- Help the views to present the data

### Controllers
- Coordinator between the models and views
- Accesses data, whether from the database through models, or from APIs
- Sets data in instance variables

### Routes
- Determines which controller and which of its action to run
- Maps URLs to a certain controller#action


## Challenges

1. The API gives us temperatures in Kelvin. Convert it to Celsius
2. Display the maximum temperature
3. Create a view helper to format Celsius 24°C
4. Add humidity and pressure to your #show page too
5. Add the countries gem and display the full name of the country on the cities #show page