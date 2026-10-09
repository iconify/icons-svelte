<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-s9c5bkm.css';
import '../../css/u/uyag2jl5g.css';
import '../../css/l/l4v9huevr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o-s9c5bkm"/><path class="uyag2jl5g"/><path class="l4v9huevr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-shading-20-bold" {...props}></Icon>
