<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv2l5-hbm.css';
import '../../css/j/jw1hfib5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGVLcjBd1s" class="tv2l5-hbm"/><path id="SVGhvPpKd0d" class="jw1hfib5l"/></defs><use href="#SVGVLcjBd1s"/><use href="#SVGhvPpKd0d"/><use href="#SVGVLcjBd1s"/><use href="#SVGhvPpKd0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:up-right" {...props}></Icon>
