<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v57k_lqgn.css';
import '../../css/c/cql0n4wpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v57k_lqgn"/><path class="cql0n4wpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:towels-20-bold" {...props}></Icon>
