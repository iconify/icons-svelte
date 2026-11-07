<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp6qz_ktz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yp6qz_ktz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:shield-infinity" {...props}></Icon>
