<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j56igpbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j56igpbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:search" {...props}></Icon>
