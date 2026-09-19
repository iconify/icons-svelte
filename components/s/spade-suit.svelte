<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv-h0ub1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iv-h0ub1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:spade-suit" {...props}></Icon>
