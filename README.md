Para comenzar a desarrollar

## Instalo las dependencias (leer el archivo package.json)

```sh
npm i
npm install
```

## Arrancar el servidor de desarrollo

```sh
npm run dev
```

## Crear un alias de Git

```sh
git config --global alias.s "status --short"
git config --global alias.ll "log --oneline"
git config --global --unset alias.s # Eliminar alias
git config --global --get-regexp alias # Listar alias
```

## Cuando quiera subirlo por ejemplo a netifly
Este comando va a terminar generando una carpeta build.

```sh
npm run build
```
