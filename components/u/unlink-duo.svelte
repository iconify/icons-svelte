<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4_ab59fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="b4_ab59fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:unlink-duo" {...props}></Icon>
