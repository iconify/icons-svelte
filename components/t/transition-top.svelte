<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh65d-5az.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zh65d-5az"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:transition-top" {...props}></Icon>
