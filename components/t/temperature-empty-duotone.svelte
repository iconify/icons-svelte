<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d1atvth_n"/><path class="o986qobmf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:temperature-empty-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.d1atvth_n) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 6C7 3.2386 9.2386 1 12 1C14.7614 1 17 3.2386 17 6L17 11.101C18.282 12.4094 19 14.1682 19 16C19 19.866 15.866 23 12 23C8.134 23 5 19.866 5 16C5 14.1682 5.718 12.4094 7 11.101L7 6Z");
}

:global(.o986qobmf) {
  d: path("M13.5 16C13.5 16.8284 12.8284 17.5 12 17.5C11.1716 17.5 10.5 16.8284 10.5 16C10.5 15.1716 11.1716 14.5 12 14.5C12.8284 14.5 13.5 15.1716 13.5 16Z");
}

</style>
