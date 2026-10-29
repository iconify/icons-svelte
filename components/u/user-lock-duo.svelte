<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/a_0c-vozs.css';
import '../../css/n/nexbjnbng.css';
import '../../css/r/rkrwd5pdm.css';
import '../../css/l/ljeitrr-k.css';
import '../../css/y/ybhe00r-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="a_0c-vozs"/><path class="nexbjnbng wm-s"/><path class="rkrwd5pdm wm-s"/><path class="ljeitrr-k"/><path class="wm-a ybhe00r-q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:user-lock-duo" {...props}></Icon>
