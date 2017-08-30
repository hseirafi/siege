- test benchmark http://127.0.0.1 with concurrent thread (connection) 10 for 60 seconds

siege -c10 -t60s http://127.0.0.1

- test benchmark http://127.0.0.1 with no limit concurrent thread (connection) for 60 seconds

siege -b -t60s http://127.0.0.1