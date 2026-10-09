<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi2c5z44e.css';
import '../../css/x/xmsbzrzmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fi2c5z44e"/><path class="xmsbzrzmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:terminal-20-bold" {...props}></Icon>
