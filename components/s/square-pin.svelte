<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6r8g0bbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="p6r8g0bbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:square-pin" {...props}></Icon>
