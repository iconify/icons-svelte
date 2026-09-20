<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf363obkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sf363obkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:xing-square" {...props}></Icon>
