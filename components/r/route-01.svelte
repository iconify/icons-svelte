<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/u/ugw1omula.css';
import '../../css/t/tke4h5b0x.css';
import '../../css/n/nksj0vbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ugw1omula"/><circle class="tke4h5b0x"/><path class="nksj0vbih"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:route-01" {...props}></Icon>
