<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfvc9yb6v.css';
import '../../css/z/zg5f-yb0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qfvc9yb6v"/><path class="zg5f-yb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sticker-20" {...props}></Icon>
