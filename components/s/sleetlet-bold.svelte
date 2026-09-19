<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om8b7-bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="om8b7-bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sleetlet-bold" {...props}></Icon>
