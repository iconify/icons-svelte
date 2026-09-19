<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_6l8gk2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j_6l8gk2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:sun-behind-large-cloud" {...props}></Icon>
