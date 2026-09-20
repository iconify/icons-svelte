<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9blw_16z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r9blw_16z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tsdproxy-light" {...props}></Icon>
