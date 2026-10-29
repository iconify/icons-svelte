<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/ea84mbb_c.css';
import '../../css/g/gawr9cban.css';
import '../../css/z/zzgumwbxx.css';
import '../../css/p/p05kv_btd.css';
import '../../css/b/bovtacbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ea84mbb_c wm-k"/><path class="gawr9cban wm-shadow"/><path class="wm-k zzgumwbxx"/><path class="p05kv_btd wm-k"/><path class="bovtacbyz wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:smartphone-engrave" {...props}></Icon>
