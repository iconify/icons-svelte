<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x24r8mbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="x24r8mbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:s-bold" {...props}></Icon>
