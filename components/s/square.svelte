<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ese5zsb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ese5zsb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:square" {...props}></Icon>
