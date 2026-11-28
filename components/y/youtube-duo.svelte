<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqp4n6_wf.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/g2f38_bgz.css';
import '../../css/x/xgirfrbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary zqp4n6_wf"/><g class="dt0cm9dhy primary"><path class="g2f38_bgz"/><path class="xgirfrbpu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:youtube-duo" {...props}></Icon>
