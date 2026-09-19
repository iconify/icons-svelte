<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e296fw0ge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="e296fw0ge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:ruler-combined" {...props}></Icon>
