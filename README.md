# Comandos basicos en Git

Este repo es una recopilación de comandos mas utilizados en Git para programadores.

## Para iniciar git se usa el comando:

```javascript
  git init
```

## ver que estado del git:

```javascript
  git status
```

## añadir archivos individuales al git:

```javascript
  git add 'nombre del archivo' (incluir extención)
```

## añadir todos los archivos al git:

```javascript
  git add .
```

## Crear commits:

```javascript
  git commit -m 'nombre del commit'
```

## Ver los commits:

```javascript
  git log
```

## Crear branch main:

```javascript
  git branch -M main
```

## Ver los branch creados:

```javascript
  git branch
```

## Añadir un remote al git:

```javascript
  git remote add origin https://github.com/'USERNAME'/'NOMBRE DEL REPO'.git
```

## Hacer push al git:

```javascript
  git push -u 'remote name' 'branch name' (ejemplo: git push -u origin main)
```

