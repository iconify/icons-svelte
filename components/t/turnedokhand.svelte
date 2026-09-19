<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6rqk4blh.css';
import '../../css/r/ru1qjebin.css';
import '../../css/j/jshgl_dcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m6rqk4blh"/><path class="ru1qjebin"/><path class="jshgl_dcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:turnedokhand" {...props}></Icon>
