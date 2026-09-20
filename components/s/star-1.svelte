<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa8kv5a7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sa8kv5a7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:star-1" {...props}></Icon>
