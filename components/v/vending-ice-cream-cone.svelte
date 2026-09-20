<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnw561b3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rnw561b3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:vending-ice-cream-cone" {...props}></Icon>
