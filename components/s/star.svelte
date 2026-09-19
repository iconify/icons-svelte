<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-gz_3rkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d-gz_3rkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:star" {...props}></Icon>
