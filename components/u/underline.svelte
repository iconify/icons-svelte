<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdpzmacwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="sdpzmacwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:underline" {...props}></Icon>
