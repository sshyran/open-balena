# Challenges
1. How to set service or device environment variables from the device for the device?
    1.1 Provide User API token to the service and let the container on the device call the api with the token to set the environment
2. How to provide the self-signed certificate files to the user?
    2.1 Maybe a netcat (nc) can listen to curl request and returns the .PEM file
3. How to deal with updating version files of the images?
    3.1 For now the image versions are hardcoded
4. Mounting environment volumne to ahve env files to source before starting
    4.1 try if sourcing export environment will be available in the service
