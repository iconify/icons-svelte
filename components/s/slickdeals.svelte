<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r13vadc4w.css';
import '../../css/c/cxb1kbche.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r13vadc4w"/><path class="cxb1kbche"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:slickdeals" {...props}></Icon>
