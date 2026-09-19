<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh0-fjbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gh0-fjbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:stratus" {...props}></Icon>
