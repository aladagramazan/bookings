# bookings
bookings with golang


go mod init github.com/aladagramazan/bookings

rm go.sum

go mod tidy


curl -s http://localhost:8080/search-availability-json | jq 