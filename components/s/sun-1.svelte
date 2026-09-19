<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdicp7lrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="jdicp7lrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sun-1" {...props}></Icon>
