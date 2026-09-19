<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-8x2bf4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g-8x2bf4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:s" {...props}></Icon>
