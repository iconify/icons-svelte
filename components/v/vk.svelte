<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trs3z3bbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="trs3z3bbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:vk" {...props}></Icon>
