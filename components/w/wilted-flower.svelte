<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8gv4p9ia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x8gv4p9ia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:wilted-flower" {...props}></Icon>
