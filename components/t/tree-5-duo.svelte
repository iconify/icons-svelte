<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz2twmlmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="nz2twmlmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tree-5-duo" {...props}></Icon>
