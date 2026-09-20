<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqzjg74_k.css';
import '../../css/x/xf-y1rnlx.css';
import '../../css/i/is60ubtfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="lqzjg74_k"/><path class="xf-y1rnlx"/><path clip-rule="evenodd" class="is60ubtfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:user-reading" {...props}></Icon>
