<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czpmmccki.css';
import '../../css/z/zp_npu0od.css';
import '../../css/t/tkr1nkhyy.css';
import '../../css/b/byf6y2fkx.css';
import '../../css/q/qpd__bb7t.css';
import '../../css/o/o6p1xcb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="czpmmccki"/><path class="zp_npu0od"/><path class="tkr1nkhyy"/><path class="byf6y2fkx"/><path class="qpd__bb7t"/><path class="o6p1xcb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:ss-4x3" {...props}></Icon>
