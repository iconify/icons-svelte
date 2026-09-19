<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wsz48i5vf.css';
import '../../css/m/mfueqsb7p.css';
import '../../css/y/yn7zagbyu.css';
import '../../css/h/hdqeu7brz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="wsz48i5vf"/><path class="mfueqsb7p"/><rect class="yn7zagbyu"/><path class="hdqeu7brz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:router" {...props}></Icon>
