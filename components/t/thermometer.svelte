<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bto_4-vps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bto_4-vps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:thermometer" {...props}></Icon>
