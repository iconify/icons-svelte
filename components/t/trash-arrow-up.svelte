<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv-1gie-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="yv-1gie-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:trash-arrow-up" {...props}></Icon>
