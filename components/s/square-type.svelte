<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lk2gmgbqk.css';
import '../../css/d/d0qdg3dzf.css';
import '../../css/x/xxgdw-btn.css';
import '../../css/f/fkpiqrb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lk2gmgbqk"/><path class="d0qdg3dzf"/><path class="xxgdw-btn"/><path class="fkpiqrb4a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-type" {...props}></Icon>
