> [!IMPORTANT]
> **Replaced by [`@arraypress/waveform-vue`](https://www.npmjs.com/package/@arraypress/waveform-vue) 2.0.** Import from `@arraypress/waveform-vue/playlist` instead — one package per framework, with a sub-path per component ([repo](https://github.com/WaveformPlayer/vue), [migration guide](https://docs.waveformplayer.com/getting-started/migrating-from-1x/)).
> This repository is archived and the npm package is deprecated; its 1.x releases keep working.

<div align="center">

# Waveform Playlist for Vue

**Vue 3 component wrapper for `@arraypress/waveform-playlist`.** A declarative multi-track playlist player with chapters, markers, and an exposed imperative navigation API.

[![npm version](https://img.shields.io/npm/v/@arraypress/waveform-playlist-vue?style=flat-square&labelColor=09090b&color=3f3f46)](https://www.npmjs.com/package/@arraypress/waveform-playlist-vue)
[![license](https://img.shields.io/npm/l/@arraypress/waveform-playlist-vue?style=flat-square&labelColor=09090b&color=3f3f46)](https://github.com/arraypress)

**[Documentation](https://docs.waveformplayer.com/)** · [npm](https://www.npmjs.com/package/@arraypress/waveform-playlist-vue)

</div>

---

## Install

```bash
npm install @arraypress/waveform-playlist-vue @arraypress/waveform-playlist @arraypress/waveform-player vue
```

```vue
<script setup lang="ts">
import { WaveformPlaylist } from '@arraypress/waveform-playlist-vue';
</script>

<template>
  <WaveformPlaylist :tracks="[{ url: '/a.mp3', title: 'A', artist: 'Artist' }]" />
</template>
```

## Documentation

Full props, the imperative API, and SSR notes live in the docs.

### -> [docs.waveformplayer.com](https://docs.waveformplayer.com/)

[Vue guide](https://docs.waveformplayer.com/frameworks/vue/) — install, props, the imperative API, and SSR notes. All four Vue wrappers (player / bar / playlist) are on that page.

## License

MIT © [ArrayPress](https://github.com/arraypress)
