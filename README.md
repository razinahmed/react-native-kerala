# React Native Kerala

![React Native](https://img.shields.io/badge/React_Native-Components-61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E)
![License](https://img.shields.io/badge/License-MIT-green)

A React Native component library featuring Kerala-themed UI elements. Build mobile applications with design patterns inspired by Kerala's visual culture, including traditional color palettes and culturally relevant component styles.

## Features

- Kerala-themed React Native components for iOS and Android
- Pre-configured color palette based on traditional Kerala aesthetics
- Dark-mode-ready theme with vibrant accent colors
- Consistent cross-platform rendering
- Lightweight with minimal peer dependencies

## Tech Stack

| Technology   | Purpose                |
|--------------|------------------------|
| React Native | Mobile UI framework    |
| JavaScript   | Programming language   |
| CSS3         | Web theme reference    |
| Make         | Build automation       |

## Quick Start

1. Clone the repository:

```bash
git clone https://github.com/razinahmed/react-native-kerala.git
cd react-native-kerala
```

2. Install dependencies:

```bash
npm install
```

3. Import components into your app:

```jsx
import { KeralaButton, KeralaCard } from 'react-native-kerala';

<KeralaCard>
  <KeralaButton title="Explore Kerala" onPress={handlePress} />
</KeralaCard>
```

## Theme

The Kerala theme provides a curated set of colors:

| Token        | Value     | Description           |
|--------------|-----------|-----------------------|
| `primary`    | `#00d4aa` | Primary accent        |
| `background` | `#1e1e2e` | Base background       |

## Build

```bash
make build
make test
```

## Project Structure

```
react-native-kerala/
  styles/
    theme.css       # Theme reference
  Makefile          # Build commands
  LICENSE           # MIT License
```

## Contributing

Contributions are welcome. Please test components on both iOS and Android before submitting pull requests.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
