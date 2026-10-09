<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhx89lryx.css';
import '../../css/r/r07ubeb7t.css';
import '../../css/d/d6b0ntifu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dhx89lryx"/><path class="r07ubeb7t"/><path class="d6b0ntifu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-charging-20" {...props}></Icon>
