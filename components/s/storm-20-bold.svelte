<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_vfm6cfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r_vfm6cfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:storm-20-bold" {...props}></Icon>
