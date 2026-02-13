Para arrancar por primera vez: docker-compose up -d

Para cambiar de rama y actualizar:  1. git -C TSTWEB checkout rama-nueva
                                    2. docker-compose up --build -d

Para resetear la base de datos si cambias el SQL: 
docker-compose down -v y luego, docker-compose up -d