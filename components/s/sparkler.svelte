<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hsgg6j0lp.css';
import '../../css/m/m3mfq9x2i.css';
import '../../css/j/jgwm0beal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="hsgg6j0lp"/><path class="m3mfq9x2i wm-a"/><path class="jgwm0beal wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sparkler" {...props}></Icon>
