<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/r/r2jxn3bxo.css';
import '../../css/b/brroavbfx.css';
import '../../css/c/cl09nonwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="r2jxn3bxo"/><path clip-rule="evenodd" class="brroavbfx"/><path class="cl09nonwk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sofa-sharp-duotone" {...props}></Icon>
