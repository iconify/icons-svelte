<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef7rbpz1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ef7rbpz1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:utility-shutoff-with-cable" {...props}></Icon>
