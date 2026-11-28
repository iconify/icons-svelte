<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mtz981hll.css';
import '../../css/v/vywcsyufc.css';
import '../../css/d/doesvwojv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mtz981hll"/><path class="vywcsyufc"/><path class="doesvwojv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:text-cursor-duo" {...props}></Icon>
