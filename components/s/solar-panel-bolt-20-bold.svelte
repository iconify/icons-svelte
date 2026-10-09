<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obu46ub-t.css';
import '../../css/k/kzkq8kbod.css';
import '../../css/b/bzo0k_whu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="obu46ub-t"/><path class="kzkq8kbod"/><path class="bzo0k_whu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-panel-bolt-20-bold" {...props}></Icon>
