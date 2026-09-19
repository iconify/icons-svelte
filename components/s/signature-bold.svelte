<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0ty2nbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="d0ty2nbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:signature-bold" {...props}></Icon>
