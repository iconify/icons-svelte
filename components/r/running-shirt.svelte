<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt_nuk8ge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rt_nuk8ge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:running-shirt" {...props}></Icon>
