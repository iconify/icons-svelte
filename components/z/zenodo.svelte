<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kagb8yi_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="colorfff kagb8yi_r svgShape"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:zenodo" {...props}></Icon>
