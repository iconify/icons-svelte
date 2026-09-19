<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyun3gb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xyun3gb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:vsphere" {...props}></Icon>
