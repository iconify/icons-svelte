<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnu6byhtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tnu6byhtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:star-and-crescent" {...props}></Icon>
