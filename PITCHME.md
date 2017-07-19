# Dockerizing Rails

More precisely, using Docker and Docker-Compose in creating local development environments for Ruby-on-Rails applications

---

## Plan

- follow the official tutorial [https://docs.docker.com/compose/rails/](https://docs.docker.com/compose/rails/)
- make the database persist using Docker volumes
- try the same for a legacy project on Rails, e.g. [https://github.com/fulcrum-agile/fulcrum](https://github.com/fulcrum-agile/fulcrum)

---

## Prerequisites

Assume that Docker and Docker-Compose are installed on the workstation:

```
$ docker -v
Docker version 17.05.0-ce, build 89658be
$ docker-compose -v
docker-compose version 1.14.0, build c7bdf9e
```

---

## The repository

To follow along easier, clone the repository for this talk:

[https://github.com/yurivyatkin/docorails](https://github.com/yurivyatkin/docorails)

Checkout to branch 1-bootstrap, and see the files.
