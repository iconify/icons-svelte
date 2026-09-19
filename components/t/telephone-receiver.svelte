<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo4qn1t0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vo4qn1t0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:telephone-receiver" {...props}></Icon>
