

# Tailwind Css setup

### Step: 01

```
npx tailwindcss -o styles.css
```
### Step: 02

```
npx tailwindcss -o styles.css --jit --purge './**/*.html'
```
### Step: 03

```
npx tailwindcss -o styles.css --jit --purge './**/*.html' -w
```
### Step: 04 

#### Custom css

```
npx tailwindcss -i tailwind.css -o styles.css --jit --purge './**/*.html' -w
```

#### Tailwind css help
```
npx tailwindcss -h
```

#### Minify css
```
npx tailwindcss -i tailwind.css -o styles.css --jit --minify --purge './**/*.html' -w
```
