<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-4cds9bz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i-4cds9bz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shark-dorsal-fin-in-water" {...props}></Icon>
