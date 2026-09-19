<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmffgr_ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="kmffgr_ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:sort" {...props}></Icon>
