<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfljk-bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dfljk-bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:utility-shutoff-with-bolt" {...props}></Icon>
