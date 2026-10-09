<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhx3t-acu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fhx3t-acu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:waterfall-20" {...props}></Icon>
