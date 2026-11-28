<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy_ggab6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="gy_ggab6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:telescope-light" {...props}></Icon>
