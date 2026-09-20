<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frr12ubyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frr12ubyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:water-plus" {...props}></Icon>
