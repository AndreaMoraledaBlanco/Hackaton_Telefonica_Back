# HackatonF5Back
Repo del front: https://github.com/LorelizDev/hackaton-F5-G1-2024

Presentación de proyecto SafeSoul, app enfocada a la Salud Mental:
https://www.canva.com/design/DAGSbDMNKFo/r7XsMw7M9bf0OJdp1OKd6g/edit?utm_content=DAGSbDMNKFo&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

Repo del backend del hackaton

Estructua del .env para trabajar en local con Docker:
- DB_USERNAME=user
- DB_PASSWORD=password para el user
- DB_ROOT_PASSWORD=password para el root
- DB_HOST=mysql-db
- DB_PORT=3306
- DB_NAME=safe_soul

Estructura del .env para que el bot funcione:
- HUGGINGFACEHUB_API_TOKEN= "token de hf"//
- USER_AGENT= "nombre del bot"//

Para construir el docker ejecutar en la carpeta raiz:
- docker-compose build --up
