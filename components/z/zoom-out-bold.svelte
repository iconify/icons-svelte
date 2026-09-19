<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n416p013c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="n416p013c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:zoom-out-bold" {...props}></Icon>
