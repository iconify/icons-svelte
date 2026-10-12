<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9mf9qlbg.css';
import '../../css/w/wj8c8qbtx.css';
import '../../css/q/qh3-d7bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w9mf9qlbg"/><path class="wj8c8qbtx"/><path class="qh3-d7bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smartphone-check-20" {...props}></Icon>
