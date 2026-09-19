<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpkcm5but.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="mpkcm5but"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:square-half-outline" {...props}></Icon>
