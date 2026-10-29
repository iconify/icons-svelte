<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/f19ei9bez.css';
import '../../css/w/wfupqcc6c.css';
import '../../css/j/jd-9hyvzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="f19ei9bez"/><path class="wfupqcc6c wm-a"/><path class="jd-9hyvzp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:stroller" {...props}></Icon>
