<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6f6i0bcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x6f6i0bcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tools" {...props}></Icon>
