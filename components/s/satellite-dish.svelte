<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yejevkv4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yejevkv4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:satellite-dish" {...props}></Icon>
