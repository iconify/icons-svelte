<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0hu2obfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="m0hu2obfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:ticket-1-bold" {...props}></Icon>
