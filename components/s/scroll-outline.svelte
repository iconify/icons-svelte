<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iooj79bob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="iooj79bob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:scroll-outline" {...props}></Icon>
