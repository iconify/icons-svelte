<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzcm5lbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="hzcm5lbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tree-4" {...props}></Icon>
