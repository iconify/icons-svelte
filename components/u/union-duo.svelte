<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx6lrpb3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="bx6lrpb3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:union-duo" {...props}></Icon>
