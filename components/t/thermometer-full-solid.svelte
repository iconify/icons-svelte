<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2u6px6tw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q2u6px6tw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:thermometer-full-solid" {...props}></Icon>
