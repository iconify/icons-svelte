<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8ji8225f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="b8ji8225f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sort-1-bold" {...props}></Icon>
