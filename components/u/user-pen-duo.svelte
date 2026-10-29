<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/a_0c-vozs.css';
import '../../css/x/xlm5w-bhh.css';
import '../../css/j/j10ehyblf.css';
import '../../css/l/ljeitrr-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="a_0c-vozs"/><path class="wm-s xlm5w-bhh"/><path class="j10ehyblf wm-s"/><path class="ljeitrr-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:user-pen-duo" {...props}></Icon>
