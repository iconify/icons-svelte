<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rium4wb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rium4wb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:subsetting" {...props}></Icon>
