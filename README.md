# React Lain Snippets for Zed

Snippets de React para Zed enfocados en velocidad, sin imports automáticos y con soporte para `TSX` y `JSX`.

Inspirada en `zed-react-snippets` de shonebinu:
`https://github.com/shonebinu/zed-react-snippets`

## Features

- Snippets para componentes funcionales (`rafce`, `rfc`)
- Snippets para hooks básicos (`us`, `ue`)
- Soporte para:
  - `TSX` mediante `snippets/tsx.json`
  - `JSX` mediante `snippets/javascript.json` (requisito de Zed)

## Included Snippets

### TSX and JSX

- `rafce` -> React Arrow Function Component + `export default`
- `rfc` -> React Functional Component + `export default`
- `us` -> `useState`
- `ue` -> `useEffect`

## Install

### Option 1: Local development install

1. Clona este repositorio.
2. Abre Zed.
3. Ve a extensiones y carga la carpeta local de la extensión.

### Option 2: From extension registry

Cuando esté publicada, instala la extensión por su id: `react-lain-snippets`.

## Usage

1. Abre un archivo `.tsx` o `.jsx`.
2. Escribe un prefijo, por ejemplo `rafce`.
3. Presiona `Tab` para expandir.

## Important Zed Notes

- En Zed, los snippets para JSX deben estar en `javascript.json` (no en `jsx.json`).
- Algunas variables avanzadas de snippets de VS Code (por ejemplo `TM_FILENAME_BASE`) pueden no comportarse igual en Zed.

## Project Structure

- `extension.toml`
- `snippets/tsx.json`
- `snippets/javascript.json`
- `CHANGELOG.md`

## Contributing

Contribuciones y mejoras son bienvenidas.

Este proyecto usa licencia MIT, asi que puedes forkear, copiar, adaptar y reutilizar el codigo respetando los terminos de `LICENSE`.

1. Haz un fork.
2. Crea una rama (`feat/nueva-mejora`).
3. Haz tus cambios.
4. Abre un Pull Request.

Lee `CONTRIBUTING.md` para más detalle.

## Security

Si encuentras un problema de seguridad, revisa `SECURITY.md`.

## License

Este proyecto se distribuye bajo la licencia incluida en `LICENSE`.
