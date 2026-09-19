<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2e80kbeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="p2e80kbeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wechat-stroke-12" {...props}></Icon>
