<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3d7bpber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l3d7bpber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:table-move-column-before-rtl" {...props}></Icon>
