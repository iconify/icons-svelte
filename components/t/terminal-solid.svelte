<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rktte6bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rktte6bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:terminal-solid" {...props}></Icon>
