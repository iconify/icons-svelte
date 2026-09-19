<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn6481bwr.css';
import '../../css/p/pxkrmsbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rn6481bwr"/><path class="pxkrmsbhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:temperature-min" {...props}></Icon>
