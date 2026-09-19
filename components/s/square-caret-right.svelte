<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8mxwke8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="h8mxwke8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:square-caret-right" {...props}></Icon>
