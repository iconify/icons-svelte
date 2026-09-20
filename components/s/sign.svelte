<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlb_u5jaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlb_u5jaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sign" {...props}></Icon>
