<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wccjcn_8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wccjcn_8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:set-center-right" {...props}></Icon>
