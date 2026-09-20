<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvkc8whus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="pvkc8whus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:swimming" {...props}></Icon>
