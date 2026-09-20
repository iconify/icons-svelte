<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfu6s6g3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lfu6s6g3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:wrench" {...props}></Icon>
