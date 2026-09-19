<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh1aksb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rh1aksb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:utility-expense" {...props}></Icon>
