<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi2_bml3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="yi2_bml3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:skiing" {...props}></Icon>
