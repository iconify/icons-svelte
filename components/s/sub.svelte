<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd6kdgv8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rd6kdgv8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:sub" {...props}></Icon>
