<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/a/a-yw60bso.css';
import '../../css/r/rel7kcbvz.css';
import '../../css/a/a_eoytg9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="a-yw60bso"/><circle class="rel7kcbvz"/><path class="a_eoytg9v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:spline-pointer" {...props}></Icon>
