<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc9hztbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":432};
const content = `<path class="hc9hztbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:tv-alt-play" {...props}></Icon>
