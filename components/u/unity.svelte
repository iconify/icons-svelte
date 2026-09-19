<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd_lskbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="zd_lskbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:unity" {...props}></Icon>
