<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyujnpuhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uyujnpuhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-minus-20-bold" {...props}></Icon>
