<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_3d0-bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":383.2,"height":196.4};
const content = `<path class="s_3d0-bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:whop-dark" {...props}></Icon>
