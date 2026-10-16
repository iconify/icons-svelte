<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1pekhtvh.css';
import '../../css/g/gipfg7brd.css';
import '../../css/l/le6qx_s4l.css';
import '../../css/m/mpz045b2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q1pekhtvh"/><path class="gipfg7brd"/><path class="le6qx_s4l"/><path class="mpz045b2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shovel-20" {...props}></Icon>
