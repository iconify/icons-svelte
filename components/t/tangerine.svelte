<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuzlowbon.css';
import '../../css/m/mrseh9rmw.css';
import '../../css/o/o0lf53bjy.css';
import '../../css/o/o80fjacmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fuzlowbon"/><path class="mrseh9rmw"/><path class="o0lf53bjy"/><path class="o80fjacmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:tangerine" {...props}></Icon>
