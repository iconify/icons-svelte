<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poibn3b_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="poibn3b_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:stand-here" {...props}></Icon>
