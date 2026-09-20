<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/a/alk7dvb9p.css';
import '../../css/n/nmjbsk1wt.css';
import '../../css/q/qg4ud0b0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="alk7dvb9p"/><path class="nmjbsk1wt"/><path class="qg4ud0b0f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:tag-horizontal-start-percent-sharp-duotone" {...props}></Icon>
