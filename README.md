# Deploy the Application

Let us deploy the full-fledged app using docker-compose:

```bash
$ docker-compose up -d
```

# Testing the App

After the application starts, navigate to [http://localhost:80](http://localhost:80) in your web browser or run the following commands:

```bash
curl localhost:80
```

Output:

```
web1: Total number of visits is: 1
```

```bash
curl localhost:80
```

Output:

```
web1: Total number of visits is: 2
```

```bash
$ curl localhost:80
```

Output:

```
web2: Total number of visits is: 3
```

```bash
$ curl localhost:80
```

Output:

```
web2: Total number of visits is: 4
```
