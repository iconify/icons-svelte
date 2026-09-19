<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="xkbqnyrnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:up-right-arrow" {...props}></Icon>
<style>
:global(.xkbqnyrnd) {
  fill: currentColor;
  d: path("M53.213 10.786c-11.715-11.715-30.711-11.715-42.426 0c-11.716 11.717-11.716 30.711 0 42.428c11.715 11.715 30.711 11.715 42.426 0c11.716-11.717 11.716-30.711 0-42.428M45 41.132l-7.585-7.414l-13.458 13.281L17 39.954l13.218-13.391l-7.343-7.564H45z");
}

</style>
