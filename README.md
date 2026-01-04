# bookings
bookings with golang


go mod init github.com/aladagramazan/bookings

rm go.sum

go mod tidy

go get github.com/asaskevich/govalidator --> for email validation

curl -s http://localhost:8080/search-availability-json | jq 


feat: Add reservation summary handler with session-based flash messages

- Add ReservationSummary handler to display booking confirmation
- Implement flash/warning/error notifications using notie
- Add PopString session support for one-time messages
- Comment out notification template blocks temporarily
