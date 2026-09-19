<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2l7ej-yh.css';
import '../../css/x/xtkb6fvqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f2l7ej-yh"/><path class="xtkb6fvqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:touch-1-down" {...props}></Icon>
