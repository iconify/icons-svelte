<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx8zhcwih.css';
import '../../css/z/zcanx4ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wx8zhcwih"/><path class="zcanx4ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:uranium-20" {...props}></Icon>
