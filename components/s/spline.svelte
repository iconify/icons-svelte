<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/e/eypk3skau.css';
import '../../css/k/kf2q3hbnt.css';
import '../../css/p/pb4zwjt1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="eypk3skau"/><circle class="kf2q3hbnt"/><path class="pb4zwjt1h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:spline" {...props}></Icon>
