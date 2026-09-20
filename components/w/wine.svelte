<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4s7hfbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="j4s7hfbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:wine" {...props}></Icon>
