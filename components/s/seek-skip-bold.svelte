<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3yyn7pgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="z3yyn7pgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:seek-skip-bold" {...props}></Icon>
