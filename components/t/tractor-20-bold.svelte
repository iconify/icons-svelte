<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yak9gybyx.css';
import '../../css/f/ftk0oxb7p.css';
import '../../css/z/z2iqjbiby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yak9gybyx"/><path class="ftk0oxb7p"/><path class="z2iqjbiby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tractor-20-bold" {...props}></Icon>
