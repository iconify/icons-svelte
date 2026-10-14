<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/t/tgumiwnon.css';
import '../../css/a/aik3ocb3t.css';
import '../../css/y/y5h7g0zml.css';
import '../../css/z/z7-_lxa9q.css';
import '../../css/l/lz_2t-b2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="tgumiwnon"/><path class="aik3ocb3t"/><path class="y5h7g0zml"/><path class="z7-_lxa9q"/><path class="lz_2t-b2y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:wallet" {...props}></Icon>
