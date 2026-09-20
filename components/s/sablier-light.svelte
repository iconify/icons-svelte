<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrp8vu0zf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rrp8vu0zf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sablier-light" {...props}></Icon>
