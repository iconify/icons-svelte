<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t675-1b2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t675-1b2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:scissors" {...props}></Icon>
