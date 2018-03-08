# semesterly-docker
Docker dev environment for semesterly

Place code under code/
 - Update settings as needed (TODO document)
run docker-compose up
When server is up, run:
  docker exec -it semub_web_1 python manage.py ingest jhu --term Spring --years 2018
  docker exec -it semub_web_1 python manage.py digest jhu
