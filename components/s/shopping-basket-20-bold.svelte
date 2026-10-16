<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knt-nibqh.css';
import '../../css/x/xysx9bb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="knt-nibqh"/><path class="xysx9bb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shopping-basket-20-bold" {...props}></Icon>
