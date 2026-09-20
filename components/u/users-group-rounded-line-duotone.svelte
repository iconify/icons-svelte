<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xkqyiwblc.css';
import '../../css/q/qaiwx9bis.css';
import '../../css/d/dt10bzeut.css';
import '../../css/e/e5joplaob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="xkqyiwblc"/><path class="qaiwx9bis"/><ellipse class="dt10bzeut"/><path class="e5joplaob"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:users-group-rounded-line-duotone" {...props}></Icon>
