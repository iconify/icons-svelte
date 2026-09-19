<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc5ft-b7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="qc5ft-b7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:sleetlet" {...props}></Icon>
