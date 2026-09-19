<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5r5sj_tl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="b5r5sj_tl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:zoom-in" {...props}></Icon>
