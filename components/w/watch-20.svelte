<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgfat0y1j.css';
import '../../css/v/voq389b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wgfat0y1j"/><path class="voq389b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:watch-20" {...props}></Icon>
