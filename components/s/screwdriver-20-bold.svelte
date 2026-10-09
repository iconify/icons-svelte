<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag31uv8-s.css';
import '../../css/n/nlpbp5but.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ag31uv8-s"/><path class="nlpbp5but"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:screwdriver-20-bold" {...props}></Icon>
