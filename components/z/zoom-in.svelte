<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thr4qybcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="thr4qybcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:zoom-in" {...props}></Icon>
