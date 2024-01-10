# Serverless-Func-Bypass-CORS-Swiggy-API

This project creates a simple serverless API to bypass CORS restrictions and fetch data from the Swiggy API. 

## Usage

The API has two endpoints:

### /api/restaurants

Fetches a list of restaurants by latitude and longitude.

Example:

```
/api/restaurants?lat=28.6139&lng=77.2090
```

### /api/restaurant/menu 

Fetches the menu for a restaurant by latitude, longitude and menu ID.

Example: 

```
/api/restaurant/menu?lat=28.6139&lng=77.2090&menuId=21981
```

## Installation

```
npm install
```

## Run the server

```
npm start
```

This will start the server on port 3000.

The API fetches data from the Swiggy API and returns it to the client. CORS restrictions are bypassed to allow cross-origin requests.

## Dependencies

- express - web framework
- cross-fetch - Fetch API wrapper supporting CORS
- cors - CORS middleware

## License

MIT
