<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdidh17-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="rdidh17-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:zero-duo" {...props}></Icon>
