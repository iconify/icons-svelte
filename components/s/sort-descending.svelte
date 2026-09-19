<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmfj29_ra.css';
import '../../css/d/dv916pbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zmfj29_ra"/><path class="dv916pbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:sort-descending" {...props}></Icon>
