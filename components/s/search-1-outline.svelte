<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or3_f5cmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="or3_f5cmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:search-1-outline" {...props}></Icon>
