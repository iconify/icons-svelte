<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw20lybgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="bw20lybgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:three-duo" {...props}></Icon>
