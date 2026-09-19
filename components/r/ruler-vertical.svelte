<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5u6034ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="p5u6034ce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:ruler-vertical" {...props}></Icon>
