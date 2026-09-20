<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/x/xcv6q1bnv.css';
import '../../css/p/pn-8f8bgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><circle class="xcv6q1bnv"/><path class="pn-8f8bgd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:travel-map-earth-2-planet-earth-globe-world" {...props}></Icon>
