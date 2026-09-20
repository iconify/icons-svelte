<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh9kv6vns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yh9kv6vns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tipi-campsite-with-pound" {...props}></Icon>
