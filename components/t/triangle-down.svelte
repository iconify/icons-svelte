<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rml11abxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rml11abxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:triangle-down" {...props}></Icon>
