<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-qpscc4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="b-qpscc4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:trash" {...props}></Icon>
