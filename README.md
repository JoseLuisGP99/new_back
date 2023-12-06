## Configuración
1. instalar dependencias:
2. instala node y las demas dependencias
3. instala prisma por que no me deja cargar la carpeta de node donde viene la dependecia de prisma

   ```bash
   npm install

4. Ejecutar las migraciones y inicia el servidor con un solo comando:
   ```bash
   
    para la bd 
   npx prisma generate #1
   npx prisma migrate dev  #2
   npx prisma db push  #3 en caso de cambios
   npm start  #Correrlo
