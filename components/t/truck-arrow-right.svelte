<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wphqavbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="wphqavbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:truck-arrow-right" {...props}></Icon>
