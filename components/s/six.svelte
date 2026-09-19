<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkrb35bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="jkrb35bsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:six" {...props}></Icon>
