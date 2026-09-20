<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/g/g5vnngb7o.css';
import '../../css/f/f3mi_ybsx.css';
import '../../css/g/gd67pabfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g5vnngb7o"/><path class="f3mi_ybsx"/><path class="gd67pabfk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:sd-card-download" {...props}></Icon>
