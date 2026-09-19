<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht453tb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ht453tb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:spray-can" {...props}></Icon>
