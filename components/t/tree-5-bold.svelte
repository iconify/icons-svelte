<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkr_rntfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="pkr_rntfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:tree-5-bold" {...props}></Icon>
