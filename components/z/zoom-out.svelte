<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txy4kbrsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="txy4kbrsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:zoom-out" {...props}></Icon>
