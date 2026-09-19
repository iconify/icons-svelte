<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd1j9ig9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":408};
const content = `<path class="jd1j9ig9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:wifi-info" {...props}></Icon>
