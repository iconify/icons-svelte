<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7me47nlj.css';
import '../../css/r/ryesqkbnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l7me47nlj"/><path class="ryesqkbnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:vegetation-height" {...props}></Icon>
