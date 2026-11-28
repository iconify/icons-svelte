<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pf7zo5b1i.css';
import '../../css/b/bpf-dccqg.css';
import '../../css/m/mwi17isqe.css';
import '../../css/n/n3vdhmblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="pf7zo5b1i"/><path class="bpf-dccqg"/><path class="mwi17isqe"/><path class="n3vdhmblp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:yen" {...props}></Icon>
