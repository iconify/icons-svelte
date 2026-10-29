<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/ktk-1bz9k.css';
import '../../css/b/btb9bc3qj.css';
import '../../css/v/v3eqelbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ktk-1bz9k"/><path class="btb9bc3qj wm-a"/><path class="v3eqelbpl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:send-duo" {...props}></Icon>
