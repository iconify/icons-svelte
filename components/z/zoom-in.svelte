<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd6863zjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="yd6863zjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:zoom-in" {...props}></Icon>
