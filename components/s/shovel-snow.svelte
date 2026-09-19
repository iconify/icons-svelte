<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dziw1abwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="dziw1abwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:shovel-snow" {...props}></Icon>
