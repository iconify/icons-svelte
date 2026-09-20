<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3etm-s9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="s3etm-s9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:search" {...props}></Icon>
