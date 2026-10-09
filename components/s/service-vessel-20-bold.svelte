<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elry085fn.css';
import '../../css/d/duddw2vqv.css';
import '../../css/y/yc0e9lbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="elry085fn"/><path class="duddw2vqv"/><path class="yc0e9lbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:service-vessel-20-bold" {...props}></Icon>
