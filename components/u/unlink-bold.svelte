<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu69tb9sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="yu69tb9sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:unlink-bold" {...props}></Icon>
