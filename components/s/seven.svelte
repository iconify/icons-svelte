<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/binaknbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="binaknbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:seven" {...props}></Icon>
