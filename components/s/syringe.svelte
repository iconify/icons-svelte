<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1rrrv9_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q1rrrv9_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:syringe" {...props}></Icon>
