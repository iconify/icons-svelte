<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi2g_bcsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hi2g_bcsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:user-clock-solid" {...props}></Icon>
