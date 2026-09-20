<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nopl6cb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="nopl6cb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:surfing" {...props}></Icon>
