<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/v/vl5-qwbrw.css';
import '../../css/t/tb5fxeb-w.css';
import '../../css/a/ah4s37bgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vl5-qwbrw"/><path class="tb5fxeb-w"/><path class="ah4s37bgk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:test-tubes-sharp-duotone" {...props}></Icon>
