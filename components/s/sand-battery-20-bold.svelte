<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-akp5bab.css';
import '../../css/c/cl0ksvb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s-akp5bab"/><path class="cl0ksvb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sand-battery-20-bold" {...props}></Icon>
