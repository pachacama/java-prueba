
# Prueba de Git

Este documento contiene una serie de comandos útiles para trabajar con Git, desde gestionar ramas hasta subir cambios al repositorio remoto.

---

## Refrescar todos los cambios que se han hecho
```bash
git fetch
````

## Ver todas mis ramas locales

```bash
git branch
```

## Crear una nueva rama desde donde estás ubicada

```bash
git checkout -b nombre-de-rama
```

## Resetear mi rama actual a una rama específica del remoto

```bash
git reset --hard origin/nombre-de-rama
```

## Cambiarte de rama

```bash
git checkout nombre-de-rama
```

## Ver el estado de mis cambios

```bash
git status
```

---

## Agregar todos los cambios al área de staging

```bash
git add .
```

## Agregar un archivo específico al área de staging

```bash
git add nombre-de-archivo
```

## Hacer un commit con mensaje

```bash
git commit -m "mensaje o comentario"
```

## Subir mis cambios al repositorio remoto

```bash
git push origin nombre-de-rama
```

## Forzar la subida de mis cambios (con precaución)

```bash
git push -f origin nombre-de-rama
```

---

## Obtener cambios de otra rama y agregarlos con squash (sin commit automático)

```bash
git merge --squash origin/nombre-de-rama
```

```

¿Quieres que también te prepare una versión en PDF o en otro formato?
```

 

