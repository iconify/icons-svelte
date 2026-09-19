<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsdq_3b3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="bsdq_3b3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:square-dashed-1" {...props}></Icon>
