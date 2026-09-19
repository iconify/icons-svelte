<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdnhdf9mj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zdnhdf9mj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:triangle-down-outline" {...props}></Icon>
