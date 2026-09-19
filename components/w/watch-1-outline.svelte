<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z10gtnb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="z10gtnb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:watch-1-outline" {...props}></Icon>
