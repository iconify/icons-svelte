<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu6eqibhi.css';
import '../../css/n/n6mum1zrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iu6eqibhi"/><path class="n6mum1zrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tablet" {...props}></Icon>
