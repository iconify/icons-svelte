<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9161fbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i9161fbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag-with-heart" {...props}></Icon>
