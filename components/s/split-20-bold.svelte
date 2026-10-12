<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0t8-abhi.css';
import '../../css/j/j30lsq6za.css';
import '../../css/g/gh5mgezjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e0t8-abhi"/><path class="j30lsq6za"/><path class="gh5mgezjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:split-20-bold" {...props}></Icon>
