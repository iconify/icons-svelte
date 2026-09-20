<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/m/mzxv1bbpg.css';
import '../../css/t/t135zx7nc.css';
import '../../css/v/vbcgq2ytz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mzxv1bbpg"/><path class="t135zx7nc"/><path class="vbcgq2ytz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:water-broken" {...props}></Icon>
