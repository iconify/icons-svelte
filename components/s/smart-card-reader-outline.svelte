<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dljs7lzik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dljs7lzik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:smart-card-reader-outline" {...props}></Icon>
