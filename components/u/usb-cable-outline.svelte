<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-pmiy5hu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n-pmiy5hu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:usb-cable-outline" {...props}></Icon>
