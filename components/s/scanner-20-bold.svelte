<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9fpfpb1i.css';
import '../../css/d/diwo_7x5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y9fpfpb1i"/><path class="diwo_7x5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scanner-20-bold" {...props}></Icon>
