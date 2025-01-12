
curl --location "http://localhost:5001/booking"--header 'Content-Type: application/json' --data '{ "owner": "66080390d0e4f489a8e0bbd0", "start_time": "2024-04-30T10:00:00.000Z", "duration_in_minutes": 30}'
curl --location "http://localhost:5001/booking" --header "Content-Type: application/json" --data "{\"owner\": \"66080390d0e4f489a8e0bbd0\", \"start_time\": \"2024-04-30T10:00:00.000Z\", \"duration_in_minutes\": 30}"
