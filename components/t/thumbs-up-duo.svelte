<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b99bgvatr.css';
import '../../css/l/lu_9qfbls.css';
import '../../css/m/mk7_fccwz.css';
import '../../css/c/cvwjuk0bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="b99bgvatr"/><path class="lu_9qfbls wm-a"/><path class="mk7_fccwz wm-a"/><path class="cvwjuk0bx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:thumbs-up-duo" {...props}></Icon>
