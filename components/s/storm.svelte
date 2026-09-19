<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frzz74bbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="frzz74bbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:storm" {...props}></Icon>
