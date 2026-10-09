<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atfdt7ybg.css';
import '../../css/i/ijiizvbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="atfdt7ybg"/><path class="ijiizvbfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:toggle-right-20-bold" {...props}></Icon>
