<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v40dffb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="v40dffb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tree-5-outline" {...props}></Icon>
