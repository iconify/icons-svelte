<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy6q70buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zy6q70buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:white-cane" {...props}></Icon>
