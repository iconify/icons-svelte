<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmci4ixfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bmci4ixfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:while-loop" {...props}></Icon>
