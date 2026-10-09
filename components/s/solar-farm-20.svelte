<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc_igi0bl.css';
import '../../css/w/wk2rzac0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="nc_igi0bl"/><path class="wk2rzac0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-farm-20" {...props}></Icon>
