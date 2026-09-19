<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-cbvub-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="l-cbvub-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:skull-bold" {...props}></Icon>
