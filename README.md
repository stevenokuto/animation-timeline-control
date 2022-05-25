# animation-timeline-control


## Usage


## Changes

- change the tick mark to second only
  - line 1292 @ timeline.ts

- disable vertical scroll
  - line 188 and line 323 @ timeline.ts
  - line 1132 _scrollByPan @ timeline.ts
  - line 1172,1193 _scrollBySelectionOutOfBounds @ timeline.ts
  
- disable cursor at time = 0
  - line 1961 @ timeline.ts

## Development

### Build

run once to install development references:

```bash
  npm install
```

Run next command to pack JavaScript as a bundle:

```bash
  npm run build
```

## Original Repo

- [animation-timeline-control](https://github.com/ievgennaida/animation-timeline-control)

## License

MIT
