<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqibj8bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wqibj8bmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:spider" {...props}></Icon>
