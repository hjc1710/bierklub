# Bier Klub

## Getting Started

Bier Klub is dockerized, so getting started is easy. First, add this line to
your hosts file (`/etc/hosts`):

```
127.0.0.1 bierklub.dev
```

Now, run the migrations: `cd bierklub && python manage.py migrate`.

After that's done, just run `docker-compose up` and then visit `bierklub.dev`.
You should be good to go!
