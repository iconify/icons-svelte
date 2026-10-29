<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/oc-a5jbga.css';
import '../../css/y/yy6sjibep.css';
import '../../css/x/xjqifybeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="oc-a5jbga"/><path class="yy6sjibep"/><path class="xjqifybeo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:zap-sketch" {...props}></Icon>
