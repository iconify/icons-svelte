<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my_j7-_xn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="my_j7-_xn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:sun" {...props}></Icon>
