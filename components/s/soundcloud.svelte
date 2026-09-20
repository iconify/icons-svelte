<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huaop5l8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="huaop5l8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:soundcloud" {...props}></Icon>
