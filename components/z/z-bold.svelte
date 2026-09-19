<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9zmu4brs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="t9zmu4brs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:z-bold" {...props}></Icon>
