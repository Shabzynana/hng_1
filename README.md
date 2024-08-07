# IpWeatherAPI

IpWeatherAPI is a simple web server with a single API endpoint that returns a greet message to visitors with their location-based weather information.

## API Endpoint

***Endpoint***: `https://hng-1-rouge.vercel.app/api/hello?visitor_name=Mark`
Response Example:
```
{
  "client_ip": "127.0.0.1",
  "location": "Lagos",
  "greeting": "Hello, Mark! The temperature is 11 degrees Celsius in Lagos."
}

```

## Setup and Deployment
1. Clone the Repository:

```
git clone https://github.com/Shabzynana/IpWeatherAPI.git
cd hng_1

```
2. Install Dependencies:


```
npm install
```
3. start application

```
npm start
```


## Technologies Used
- Node.js
- Express.js
- Ipapi (for IP geolocation)
- OpenWeatherMap API (for weather data)