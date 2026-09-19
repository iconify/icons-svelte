<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyfmew69s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xyfmew69s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:smile-beam-bold" {...props}></Icon>
