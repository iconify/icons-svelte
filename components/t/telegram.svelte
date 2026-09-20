<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f16uycbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f16uycbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:telegram" {...props}></Icon>
