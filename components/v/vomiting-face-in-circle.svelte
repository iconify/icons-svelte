<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb5rrfbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mb5rrfbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:vomiting-face-in-circle" {...props}></Icon>
