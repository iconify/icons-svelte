<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zztvcmb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="zztvcmb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:venn-outline" {...props}></Icon>
