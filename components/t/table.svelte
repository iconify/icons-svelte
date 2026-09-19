<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu2idxbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yu2idxbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:table" {...props}></Icon>
