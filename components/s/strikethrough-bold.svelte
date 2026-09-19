<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt1hw8ngl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="nt1hw8ngl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:strikethrough-bold" {...props}></Icon>
