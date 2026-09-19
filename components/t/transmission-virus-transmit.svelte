<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/w9piptbys.css';
import '../../css/m/m4w4j7bfr.css';
import '../../css/q/qz5m2hbef.css';
import '../../css/q/qw07cp7jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="w9piptbys"/><path class="m4w4j7bfr"/><path class="qz5m2hbef"/><path class="qw07cp7jn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:transmission-virus-transmit" {...props}></Icon>
