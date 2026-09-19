<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwbmeku4p.css';
import '../../css/y/yp5ecdcuz.css';
import '../../css/k/ko513mbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bwbmeku4p"/><path class="yp5ecdcuz"/><path class="ko513mbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:unlock-twotone" {...props}></Icon>
