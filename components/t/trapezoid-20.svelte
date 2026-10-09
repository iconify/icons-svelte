<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f51_hbcsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f51_hbcsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:trapezoid-20" {...props}></Icon>
