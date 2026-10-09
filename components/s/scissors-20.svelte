<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0--pbdfi.css';
import '../../css/z/zxgl3h68t.css';
import '../../css/w/wo93-6h9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p0--pbdfi"/><path class="zxgl3h68t"/><path class="wo93-6h9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scissors-20" {...props}></Icon>
