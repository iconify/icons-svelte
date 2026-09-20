<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlqxzcb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlqxzcb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:storefront-outline" {...props}></Icon>
