<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_hnosb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":383.2,"height":196.4};
const content = `<path class="l_hnosb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:whop-light" {...props}></Icon>
