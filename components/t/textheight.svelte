<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9cc2n58k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="i9cc2n58k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:textheight" {...props}></Icon>
