<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4s22dnug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="h4s22dnug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:spaghetti-monster-flying" {...props}></Icon>
