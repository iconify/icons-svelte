<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_p2sqbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b_p2sqbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:shopping-cart" {...props}></Icon>
