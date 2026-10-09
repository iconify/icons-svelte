<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt_i27b9p.css';
import '../../css/s/s60hnq-cg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mt_i27b9p"/><path class="s60hnq-cg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wrench-20" {...props}></Icon>
