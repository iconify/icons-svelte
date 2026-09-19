<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rinuwhlnp.css';
import '../../css/a/a4d9ngb1e.css';
import '../../css/u/u-p8-vvkm.css';
import '../../css/t/tziv2vbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="rinuwhlnp"><path class="a4d9ngb1e"/><path class="u-p8-vvkm"/><path class="tziv2vbmc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:three-hexagons" {...props}></Icon>
