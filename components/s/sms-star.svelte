<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/i/ikibw8b0n.css';
import '../../css/h/hkp0csiud.css';
import '../../css/k/kvz_424cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ikibw8b0n"/><path class="hkp0csiud"/><path class="kvz_424cx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sms-star" {...props}></Icon>
