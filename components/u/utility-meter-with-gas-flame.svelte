<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_vpqxbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e_vpqxbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:utility-meter-with-gas-flame" {...props}></Icon>
