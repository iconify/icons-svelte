<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq5xnlbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="wq5xnlbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:trash-1" {...props}></Icon>
