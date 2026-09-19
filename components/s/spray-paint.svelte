<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzzr42bvz.css';
import '../../css/i/ieg0qmbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fzzr42bvz"/><path class="ieg0qmbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:spray-paint" {...props}></Icon>
