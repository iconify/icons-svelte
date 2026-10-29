<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/v1u22v3kr.css';
import '../../css/l/l0yxqkbmr.css';
import '../../css/n/n5z9vnbeb.css';
import '../../css/x/x9x785x5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="v1u22v3kr"/><path class="l0yxqkbmr wm-a"/><path class="n5z9vnbeb"/><path class="wm-a x9x785x5y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shapes-duo" {...props}></Icon>
