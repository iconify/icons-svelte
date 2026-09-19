<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkkna6b0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="pkkna6b0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:shield-exclamation-bold" {...props}></Icon>
