<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxi3c60rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vxi3c60rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:teapot" {...props}></Icon>
