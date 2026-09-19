<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/una8nxqty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="una8nxqty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:start" {...props}></Icon>
