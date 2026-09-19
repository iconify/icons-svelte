<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgx473baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zgx473baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:triangular-flag" {...props}></Icon>
