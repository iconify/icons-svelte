<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcewrmbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mcewrmbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:steam-train" {...props}></Icon>
