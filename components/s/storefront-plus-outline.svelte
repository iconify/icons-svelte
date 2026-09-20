<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj194ubnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj194ubnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:storefront-plus-outline" {...props}></Icon>
