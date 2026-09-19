<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-uyx3byo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h-uyx3byo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:underline-stroke-16" {...props}></Icon>
