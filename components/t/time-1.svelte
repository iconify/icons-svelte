<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnwl7-b_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nnwl7-b_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:time-1" {...props}></Icon>
