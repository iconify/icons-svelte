<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/s/slh1_wb1o.css';
import '../../css/l/l5y23ru5w.css';
import '../../css/x/xd_s4q3ie.css';
import '../../css/j/ja7me1bvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="n1lsf0bnc"><path class="slh1_wb1o"/><g class="l5y23ru5w"><path class="xd_s4q3ie"/><path class="ja7me1bvv"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:wings" {...props}></Icon>
