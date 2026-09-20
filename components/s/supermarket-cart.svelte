<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp4964afi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fp4964afi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:supermarket-cart" {...props}></Icon>
