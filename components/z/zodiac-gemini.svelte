<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l4d4yhbsm.css';
import '../../css/m/mgp154b3r.css';
import '../../css/l/l9jmlvbqj.css';
import '../../css/u/u71yix3kf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="l4d4yhbsm"/><path class="mgp154b3r"/><path class="l9jmlvbqj"/><path class="u71yix3kf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:zodiac-gemini" {...props}></Icon>
