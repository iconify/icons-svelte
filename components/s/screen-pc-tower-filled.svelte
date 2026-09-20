<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3wdnwb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="h3wdnwb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:screen-pc-tower-filled" {...props}></Icon>
