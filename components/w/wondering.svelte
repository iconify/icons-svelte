<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t82-wgb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t82-wgb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:wondering" {...props}></Icon>
