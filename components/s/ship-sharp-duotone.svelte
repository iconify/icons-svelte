<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/u/u-_p63bcs.css';
import '../../css/j/j6v-2tbep.css';
import '../../css/z/z03o_tbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="u-_p63bcs"/><path class="j6v-2tbep"/><path class="z03o_tbrb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:ship-sharp-duotone" {...props}></Icon>
