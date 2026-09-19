<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evr01px2z.css';
import '../../css/g/gousmcrku.css';
import '../../css/c/c9bx1tjcv.css';
import '../../css/w/wrvt_6b3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="evr01px2z"/><path clip-rule="evenodd" class="gousmcrku"/><path class="c9bx1tjcv"/><path class="wrvt_6b3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:tencent-qq" {...props}></Icon>
