<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":228};
const content = `<defs><linearGradient x1="100.93%" y1="181.283%" x2="41.769%" y2="100%" id="ssvg-id-zeit-icona"><stop offset="0%" class="tlcmntu3e"/><stop offset="100%"/></linearGradient></defs><path fill="url(#ssvg-id-zeit-icona)" class="m-pnz74ui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:zeit-icon" {...props}></Icon>
<style>
:global(.m-pnz74ui) {
  d: path("M128 0l128 227.093H0z");
}

:global(.tlcmntu3e) {
  stop-color: var(--svg-color--fff, #FFF);
}

</style>
