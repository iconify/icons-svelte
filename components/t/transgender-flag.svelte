<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0dbzhzij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v0dbzhzij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:transgender-flag" {...props}></Icon>
