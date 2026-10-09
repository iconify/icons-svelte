<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq6qzmbna.css';
import '../../css/r/r0r74pb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yq6qzmbna"/><path class="r0r74pb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ticket-20-bold" {...props}></Icon>
