<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4d_gbb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n4d_gbb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:window" {...props}></Icon>
