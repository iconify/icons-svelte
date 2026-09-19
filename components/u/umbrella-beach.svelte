<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa6_aehaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="pa6_aehaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:umbrella-beach" {...props}></Icon>
