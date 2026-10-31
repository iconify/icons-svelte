<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnnk2pxpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnnk2pxpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:user-star-corner-fill-round" {...props}></Icon>
