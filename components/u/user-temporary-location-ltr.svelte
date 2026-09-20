<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhdtu4l9b.css';
import '../../css/h/hzbrfoizy.css';
import '../../css/d/do_17v_nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zhdtu4l9b"/><path class="hzbrfoizy"/><circle class="do_17v_nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:user-temporary-location-ltr" {...props}></Icon>
