<h1>Steps to run this on local</h1>

Create a db service <a href="https://console.aiven.io/signup?referral_code=c42meszphuy91p9k4p5a" target="_blank">

To run the application, the following changes are needed in the local session : 
```export DB_URL=jdbc:mysql://HOST:PORT/DATABASE?sslMode=REQUIRED```

```export DB_USER=your_aiven_username```

```export DB_PASSWORD=your_aiven_password```

Run the appplication :

```mvn spring-boot:run```
