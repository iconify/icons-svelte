<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz_1o_rty.css';
import '../../css/w/wnd3d9bhl.css';
import '../../css/c/cw2z1nomq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oz_1o_rty"/><path class="wnd3d9bhl"/><path class="cw2z1nomq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:safety-boot-20-bold" {...props}></Icon>
