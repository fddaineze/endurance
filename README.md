## Auth

- https://24h4api.000webhostapp.com/signin
```JSON
POST {
  "username": "abc",
  "password": "123"
}
```
- https://24h4api.000webhostapp.com/signup
```JSON
POST {
  "username": "abc",
  "password": "123",
  "name": "Exemplo",
  "cod": "EXP"
}
```

## Finds
- https://24h4api.000webhostapp.com/find-user
> OBS: por limitação da hospedagem gratuita, não foi possível tratar o token através do header
```JSON
POST {
  "token": "token"
}
```

- https://24h4api.000webhostapp.com/find-all-pilots
```JSON
POST {
  "token": "token"
}
```

- https://24h4api.000webhostapp.com/find-all-cars
```JSON
POST {
  "token": "token"
}
```

## Update
- https://24h4api.000webhostapp.com/update-car
```JSON
POST {
  "token": "token",
  "id": 0,
}
```

- https://24h4api.000webhostapp.com/update-name
```JSON
POST {
  "token": "token",
  "name": "exemplo"
}
```
