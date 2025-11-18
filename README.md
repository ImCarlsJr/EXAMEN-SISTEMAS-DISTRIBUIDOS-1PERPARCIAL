# EXAMEN-SISTEMAS-DISTRIBUIDOS-1PERPARCIAL
✅ PARTE 1 — Procesos e Hilos
1️⃣ Ir a la carpeta donde está el código de la parte 1
cd part1-processes-threads"

2️⃣ Ejecutar task_processor.py

(Usamos python directo del laboratorio, normalmente funciona)

python task_processor.py


Si marca error y pide ruta completa, prueba:

py task_processor.py

✅ PARTE 2 — Sistema de Almacenamiento Distribuido
1️⃣ Ir a la carpeta donde está el docker-compose.yml
cd part2-distributed-storage\distributed-storage"

2️⃣ Levantar MongoDB en Docker
docker-compose up -d

3️⃣ Verificar que los contenedores están corriendo
docker ps


Debes ver algo como:

mongo_node1   0.0.0.0:27017->27017/tcp
mongo_node2   0.0.0.0:27018->27017/tcp

4️⃣ Instalar PyMongo (una sola vez)
pip install pymongo


Si no reconoce pip:

py -m pip install pymongo

5️⃣ Ejecutar storage_system.py
python storage_system.py


O si no funciona:

py storage_system.py

🧹 Cerrar los contenedores al finalizar
docker-compose down
