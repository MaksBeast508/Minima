# Minima
docker run -d -e minima_mdspassword=123 -e minima_desktop=true -v ~/minimadocker8001:/home/minima/data -p 8001-8004:9001-9004 --restart unless-stopped --name minima8001 minimaglobal/minima:latest
