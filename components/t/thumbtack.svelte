<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp_j9ybua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yp_j9ybua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:thumbtack" {...props}></Icon>
