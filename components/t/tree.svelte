<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxmoz7bla.css';
import '../../css/y/y4npxtoda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oxmoz7bla"/><path class="y4npxtoda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tree" {...props}></Icon>
