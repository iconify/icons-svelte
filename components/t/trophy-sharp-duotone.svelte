<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/v/v0lee0ovb.css';
import '../../css/c/ckxiefb_m.css';
import '../../css/e/e8wg7vb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="v0lee0ovb"/><path class="ckxiefb_m"/><path class="e8wg7vb-j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:trophy-sharp-duotone" {...props}></Icon>
