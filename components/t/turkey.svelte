<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmxwr-bdz.css';
import '../../css/i/ipz1qcbsc.css';
import '../../css/f/f4m1aurla.css';
import '../../css/o/ov3p5cchl.css';
import '../../css/u/uuu2xx3sq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qmxwr-bdz"/><path class="ipz1qcbsc"/><path class="f4m1aurla"/><path class="ov3p5cchl"/><path class="uuu2xx3sq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:turkey" {...props}></Icon>
