# express-jwt-authentication

D'après l'article https://blog.logrocket.com/react-native-jwt-authentication-using-axios-interceptors/

Express JWT authentication example // marche avec frontend react-native-jwt-example

pour installer le server :

git clone https://github.com/cristian-rita/express-jwt-authentication.git
npm install

pour lancer le serveur :

docker run --name mongodb -d -p 27017:27017 mongo

pour créer 1 utilisateur :

curl -X POST -H "Content-Type: application/json" -d '{"email":"john@doe.com", "password":"test", "firstName":"John", "lastName":"Doe"}' http://localhost:3000/api/register

API ENDPOINTS /

/api/register
/api/login
/api/refreshToken
/api/cat
