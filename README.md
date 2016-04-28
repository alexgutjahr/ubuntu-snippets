### Show processes on given port (8080)

    lsof -i :8080

### Show privileged processes on given port (8080)

    sudo lsof -i :8080

### Forward local port (9000) to remote server via SSH tunnel

    ssh -L 9000:localhost:8080 example.com

