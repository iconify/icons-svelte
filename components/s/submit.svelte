<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u31l4ebpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="u31l4ebpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:submit" {...props}></Icon>
