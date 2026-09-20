<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/k/kfypxpbnr.css';
import '../../css/s/smmdwpb4s.css';
import '../../css/x/xstb4kblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kfypxpbnr"/><path class="smmdwpb4s"/><path class="xstb4kblq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:winds" {...props}></Icon>
