<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3-7xhb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":280,"height":480};
const content = `<path class="y3-7xhb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:smartphone-iphone" {...props}></Icon>
