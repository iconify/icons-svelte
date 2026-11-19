<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/t/tdgve6hdl.css';
import '../../css/r/rvxs6mbfh.css';
import '../../css/y/yxq0mnbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="tdgve6hdl"/><path class="rvxs6mbfh"/><path class="yxq0mnbta"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="evicons:scheduled-charging" {...props}></Icon>
