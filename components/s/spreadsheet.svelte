<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_p8vvblx.css';
import '../../css/x/xeykeqb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z_p8vvblx"/><path class="xeykeqb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:spreadsheet" {...props}></Icon>
