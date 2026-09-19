<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztnd1sx0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ztnd1sx0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:venn-diagram" {...props}></Icon>
