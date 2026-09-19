<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7kd4zr2m.css';
import '../../css/g/gc3rb1bxv.css';
import '../../css/r/rortcs8ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v7kd4zr2m"/><path class="gc3rb1bxv"/><path class="rortcs8ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:speakerwith1soundwave" {...props}></Icon>
