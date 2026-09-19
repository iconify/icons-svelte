<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aswj7bbcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aswj7bbcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:yellow-circle" {...props}></Icon>
