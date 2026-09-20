<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqc8g_bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="yqc8g_bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:transit-station" {...props}></Icon>
