<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ordbaybav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ordbaybav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:transform-code" {...props}></Icon>
