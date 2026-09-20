<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4sxabc5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4sxabc5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:star-check" {...props}></Icon>
