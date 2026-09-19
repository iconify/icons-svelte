<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcfw6kb_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="fcfw6kb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:sd-card" {...props}></Icon>
