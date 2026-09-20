<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/e/efbn1tjkf.css';
import '../../css/b/bgd_qqbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><circle class="efbn1tjkf"/><path class="bgd_qqbck"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:travel-map-globe-model-planet-earth-globe-world" {...props}></Icon>
