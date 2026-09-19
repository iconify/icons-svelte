<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m90aoem4n.css';
import '../../css/o/ojinh4u0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m90aoem4n"/><path class="ojinh4u0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:volume-off-outline" {...props}></Icon>
