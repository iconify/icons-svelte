<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/p/p88bbjrpx.css';
import '../../css/m/mm4eu-bgy.css';
import '../../css/n/n04szjpnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p88bbjrpx"/><path class="mm4eu-bgy"/><path class="n04szjpnk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:target" {...props}></Icon>
