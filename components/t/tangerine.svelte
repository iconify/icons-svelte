<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxoeqw4ry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sxoeqw4ry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:tangerine" {...props}></Icon>
