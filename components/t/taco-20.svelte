<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-wxw6w6n.css';
import '../../css/c/culelpt1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d-wxw6w6n"/><path class="culelpt1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:taco-20" {...props}></Icon>
