<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhut6ubwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hhut6ubwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:your-spotify" {...props}></Icon>
