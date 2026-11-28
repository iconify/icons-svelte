<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6_kdcctn.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/ji5e28bhq.css';
import '../../css/t/t5xtc8odw.css';
import '../../css/z/zdl_efm0l.css';
import '../../css/q/qnmufby7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6_kdcctn secondary"/><g class="dt0cm9dhy primary"><path class="ji5e28bhq"/><path class="t5xtc8odw"/><path class="zdl_efm0l"/><path class="qnmufby7n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sink-duo" {...props}></Icon>
