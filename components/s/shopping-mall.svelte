<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-3qr5bej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="d-3qr5bej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:shopping-mall" {...props}></Icon>
