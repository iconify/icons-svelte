<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyfntu4cb.css';
import '../../css/r/ryn9fxb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kyfntu4cb"/><path class="ryn9fxb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:send-horizontal-20" {...props}></Icon>
