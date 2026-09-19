<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzrrt1rbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="tzrrt1rbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:strikethrough-outline" {...props}></Icon>
