<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt1qiacqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="yt1qiacqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:shapes" {...props}></Icon>
