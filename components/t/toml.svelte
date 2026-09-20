<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ta4w4pewe"/><path class="c66oltouw"/><path class="g43_gf4-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:toml" {...props}></Icon>
<style>
:global(.c66oltouw) {
  d: path("M64.719 83.416V51.775h126.562v31.641H143.82v138.067h-31.64V83.416z");
}

:global(.g43_gf4-w) {
  fill: var(--svg-color--9c4221, #9c4221);
  d: path("M57.528 0v28.764H31.64v198.472h25.888V256H0V0z");
}

:global(.ta4w4pewe) {
  fill: var(--svg-color--9c4221, #9c4221);
  d: path("M198.472 0v28.764h25.888v198.472h-25.888V256H256V0z");
}

</style>
