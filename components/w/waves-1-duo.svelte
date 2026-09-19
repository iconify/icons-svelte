<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s66mxdb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="s66mxdb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:waves-1-duo" {...props}></Icon>
