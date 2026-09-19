<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px6thzdhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="px6thzdhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:view-toc" {...props}></Icon>
