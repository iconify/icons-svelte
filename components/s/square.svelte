<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se2hntbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="se2hntbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:square" {...props}></Icon>
