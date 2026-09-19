<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmkmgc1ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="zmkmgc1ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:search-1" {...props}></Icon>
