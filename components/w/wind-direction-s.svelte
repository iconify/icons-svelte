<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m568nkhbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1538,"height":1535};
const content = `<path class="m568nkhbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wind-direction-s" {...props}></Icon>
