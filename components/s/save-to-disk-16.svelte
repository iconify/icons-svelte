<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tznvg3blh.css';
import '../../css/g/gvyhpkbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tznvg3blh"/><path clip-rule="evenodd" class="gvyhpkbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:save-to-disk-16" {...props}></Icon>
