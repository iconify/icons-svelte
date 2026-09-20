<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlovz5nrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wlovz5nrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:star-of-david-filled-outline" {...props}></Icon>
