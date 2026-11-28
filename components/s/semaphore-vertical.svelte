<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nm0upy-ot.css';
import '../../css/s/si_kdro5v.css';
import '../../css/l/llote6btr.css';
import '../../css/i/i08jl4bew.css';
import '../../css/z/zrlh-6b7n.css';
import '../../css/z/zx8tu8xro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="nm0upy-ot"/><path class="si_kdro5v"/><path class="llote6btr"/><path class="i08jl4bew"/><path class="zrlh-6b7n"/><path class="zx8tu8xro"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:semaphore-vertical" {...props}></Icon>
