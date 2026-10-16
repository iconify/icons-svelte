<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsy-cw1ys.css';
import '../../css/o/o338q5bim.css';
import '../../css/k/k_q3cjb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tsy-cw1ys"/><path class="o338q5bim"/><path class="k_q3cjb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:text-size-20-bold" {...props}></Icon>
