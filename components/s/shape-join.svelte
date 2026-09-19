<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpghhpbnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fpghhpbnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:shape-join" {...props}></Icon>
