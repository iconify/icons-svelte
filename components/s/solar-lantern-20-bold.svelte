<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuac8wbht.css';
import '../../css/a/a1eqfi1lp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yuac8wbht"/><path class="a1eqfi1lp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-lantern-20-bold" {...props}></Icon>
