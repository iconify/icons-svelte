<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmzaum9qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fmzaum9qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:volume-low-20" {...props}></Icon>
