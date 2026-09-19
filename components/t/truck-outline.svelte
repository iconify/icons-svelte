<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re-qghbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="re-qghbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:truck-outline" {...props}></Icon>
