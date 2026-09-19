<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyumgc4hx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pyumgc4hx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:trophy" {...props}></Icon>
