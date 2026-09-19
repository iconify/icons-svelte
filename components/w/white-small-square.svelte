<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztj20xrrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ztj20xrrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:white-small-square" {...props}></Icon>
