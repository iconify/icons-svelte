<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/k/ki_sjffgz.css';
import '../../css/d/dylmm_b7q.css';
import '../../css/b/bpfx7ob2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ki_sjffgz"/><circle class="dylmm_b7q"/><path class="bpfx7ob2c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:route-off" {...props}></Icon>
