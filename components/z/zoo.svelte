<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3b0l3olj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="x3b0l3olj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:zoo" {...props}></Icon>
