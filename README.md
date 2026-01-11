# RenStack Biome

## Setup

### React (with Next.js)

Install dependencies:

```cli
pnpm add -D @biomejs/biome @renstack/biome
```

Inside `biome.json`

```json
{
  "extends": [
    "@renstack/biome/next"
  ]
}
```

### React (without Next.js)

Install dependencies:

```cli
pnpm add -D @biomejs/biome @renstack/biome
```

Inside `biome.json`

```json
{
  "extends": [
    "@renstack/biome/react"
  ]
}
```
