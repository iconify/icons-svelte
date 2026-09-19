<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn0sidbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dn0sidbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:shopify" {...props}></Icon>
