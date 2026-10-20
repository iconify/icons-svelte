<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhr_7cy8v.css';
import '../../css/j/j-pcb1b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bhr_7cy8v"/><path class="j-pcb1b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tab-key-20-bold" {...props}></Icon>
