<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf5cnuy5b.css';
import '../../css/b/bi5-4wjkp.css';
import '../../css/i/ip-t4nauu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zf5cnuy5b"/><path class="bi5-4wjkp"/><path class="ip-t4nauu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:steel-mill-20-bold" {...props}></Icon>
