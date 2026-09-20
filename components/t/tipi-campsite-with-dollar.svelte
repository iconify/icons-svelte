<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wga8-vmxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wga8-vmxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tipi-campsite-with-dollar" {...props}></Icon>
