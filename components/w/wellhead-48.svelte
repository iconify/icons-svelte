<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6x8mkney.css';
import '../../css/x/xv4m_lf6m.css';
import '../../css/p/pirgpnhwz.css';
import '../../css/u/unh33db8g.css';
import '../../css/q/q2cwzhi4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g6x8mkney"/><path class="xv4m_lf6m"/><path class="pirgpnhwz"/><path class="unh33db8g"/><path class="q2cwzhi4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wellhead-48" {...props}></Icon>
