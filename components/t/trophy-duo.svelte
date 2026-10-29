<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/jcvf7ider.css';
import '../../css/p/pfzd08f0w.css';
import '../../css/r/ri984nurg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="jcvf7ider"/><path class="pfzd08f0w"/><path class="ri984nurg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:trophy-duo" {...props}></Icon>
