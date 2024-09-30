Generar objetos a travez de API para SCM en Palo Alto Networks 

primero generar la llave con la siguiente line en la terminal 

curl -d "grant_type=client_credentials&scope=tsg_id:ID" -u USUARIO:Secret -H "Content-Type: application/x-www-form-urlencoded" -X POST https://auth.apps.paloaltonetworks.com/oauth2/access_token
