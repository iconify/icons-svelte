<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt6-vgweh.css';
import '../../css/y/yu6035bqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gt6-vgweh"/><path class="yu6035bqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wrap-text-20-bold" {...props}></Icon>
