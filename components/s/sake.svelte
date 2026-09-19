<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rogl70aes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rogl70aes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:sake" {...props}></Icon>
