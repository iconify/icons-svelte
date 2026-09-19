<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_iq0dnaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d_iq0dnaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:soccer-ball" {...props}></Icon>
