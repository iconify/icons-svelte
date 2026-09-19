<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utulh6bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="utulh6bwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:s-outline" {...props}></Icon>
