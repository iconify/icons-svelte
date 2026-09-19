<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd7i3ibcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gd7i3ibcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:window-close" {...props}></Icon>
