<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmzdm6ops.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cmzdm6ops"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:tool-box-1" {...props}></Icon>
