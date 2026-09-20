<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s35lveboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s35lveboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tram-track-crossing-striped-line" {...props}></Icon>
