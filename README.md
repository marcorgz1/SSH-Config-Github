# Configuración de clave SSH de Github

1. Comprobar la versión de Git instalada:
```sh
git --version
```
2. Configurar nombre de usuario e email globales:
```sh
git config --global user.name "Markix1"
git config --global user.email marco.valdemoro@gmail.com
```

3. Comprobar nombre de usuario e email globales:
```sh
git config --list
```
4. Crear clave SSH:
```sh
ssh-keygen -t ed25519 -C "marco.valdemoro@gmail.com"
```

5. Abrir con el editor de texto el archivo "id_clave.pub" ubicado en la carpeta "/home/nombre_usuario/.ssh" y copiar el contenido:
```sh
vi id_clave.pub
```

6. Ir al apartado de "Claves GPG y SSH" de los ajustes de Github y crear una nueva clave.
