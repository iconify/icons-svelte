<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcffi5bhx.css';
import '../../css/b/bmcqqkc-j.css';
import '../../css/v/vxcyymb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zcffi5bhx"/><path class="bmcqqkc-j"/><path class="vxcyymb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:whisk-20-bold" {...props}></Icon>
