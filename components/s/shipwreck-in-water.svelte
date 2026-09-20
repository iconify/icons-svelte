<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni3djwbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ni3djwbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shipwreck-in-water" {...props}></Icon>
