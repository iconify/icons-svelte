<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l861pkbea.css';
import '../../css/t/tvjwpgbps.css';
import '../../css/r/rrchmn0ev.css';
import '../../css/i/i0zsydbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l861pkbea wm-k"/><path class="tvjwpgbps wm-deco"/><path class="rrchmn0ev wm-k"/><path class="i0zsydbyf wm-shadow"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-valentine:zap" {...props}></Icon>
