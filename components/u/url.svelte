<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsyng3d4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tsyng3d4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:url" {...props}></Icon>
