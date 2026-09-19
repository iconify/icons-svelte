<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5vgbcb_s.css';
import '../../css/z/zpcw5vbmj.css';
import '../../css/y/ykg8hrbqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="y5vgbcb_s"/><path class="zpcw5vbmj"/><path class="ykg8hrbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:tt-4x3" {...props}></Icon>
