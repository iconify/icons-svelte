<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g7gxgs2kh.css';
import '../../css/r/r79t6gbpx.css';
import '../../css/d/dme7_ac0c.css';
import '../../css/l/ljw71xo-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="g7gxgs2kh"/><path class="r79t6gbpx"/><path class="dme7_ac0c"/><path class="ljw71xo-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:weibo" {...props}></Icon>
