<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi_hsf-aq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="mi_hsf-aq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:swagger" {...props}></Icon>
