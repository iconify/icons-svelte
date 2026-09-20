<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulu6lsb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ulu6lsb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tram-on-tram-track" {...props}></Icon>
