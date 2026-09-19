<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc95llbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="fc95llbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:sticky-note" {...props}></Icon>
