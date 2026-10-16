<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl0b0_yrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":83};
const content = `<path class="yl0b0_yrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vert" {...props}></Icon>
