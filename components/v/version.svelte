<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1wt32bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="j1wt32bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:version" {...props}></Icon>
