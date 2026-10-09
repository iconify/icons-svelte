<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/punxieblh.css';
import '../../css/z/zi252sbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="punxieblh"/><path class="zi252sbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-bolt-20-bold" {...props}></Icon>
