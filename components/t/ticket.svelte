<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxd0vacrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wxd0vacrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:ticket" {...props}></Icon>
