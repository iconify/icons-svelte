<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2807ybdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t2807ybdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:user-add" {...props}></Icon>
