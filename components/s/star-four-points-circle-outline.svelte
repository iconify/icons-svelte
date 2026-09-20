<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fntwpcewa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fntwpcewa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:star-four-points-circle-outline" {...props}></Icon>
