<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm2cx4-yg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bm2cx4-yg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:unlocked-filled" {...props}></Icon>
