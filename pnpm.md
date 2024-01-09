![pnpm](https://pnpm.io/img/pnpm-light.svg "pnpm")

# Pnpm

es como un npm pero mas veloz a la hoa de descargar los paquetes ya que lo que hace es buscar si ya lo descargastes usa esos que ya descargastes y si no lo descargaste lo descarga todo los paquetes.

## Comandos

Inicializa un nuevo projecto

`pnpm init`

si con `npm init` te genera un **package-lock.json**, con pnpm te genera un **pnpm-lock.yaml**

---

Agrega nuevos modulos, o dependencias o lo que seria en npm install

`pnpm add NOMBRE_DEPENDECIA`

---
agrega nuevas dependencias pero de desarrollor

`pnpm add -D NOMBRE_DEPENDECIA`

---
Agrega las dependencias globales

`pnpm add NOMBRE_DEPENDECIA -g`

Si no funciona entonces escriba esto:

`pnpm setup`

---

Para instalar las dependencias es con:

`pnpm i` o `pnpm install`

---

Para remover dependencias es con

`pnpm remove NOMBRE_DEPENDECIA`

---
para ejecutar algunos comando es com:

`pnpm exec COMANDO`

esto es la equivalencia a `npx COMANDO` de npm

---

ahora npx aveces se usa para crear proyecto como `npx create-react-app`, con pnpm es asi:

`pnpm dlx create-react-app`

---

ahora y si, ¿tenemos un proyecto que tiene todo su package-lock.json podemos pasarlo a pnpm?, claro que si!!, con.

`pnpm import`