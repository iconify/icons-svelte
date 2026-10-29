<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wsalesqno.css';
import '../../css/f/f_5wg0bxj.css';
import '../../css/a/araeuyb9p.css';
import '../../css/z/zci-1fbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="wsalesqno"/><path class="f_5wg0bxj wm-a"/><path class="araeuyb9p"/><path class="wm-a zci-1fbna"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:trash-2-duo" {...props}></Icon>
