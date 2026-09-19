<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv4gh3xea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zv4gh3xea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:toilet-paper" {...props}></Icon>
