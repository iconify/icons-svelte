<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qz58nqbby.css';
import '../../css/t/tx1xilbkt.css';
import '../../css/u/u0nn1qdyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="qz58nqbby"/><path class="tx1xilbkt"/><path class="u0nn1qdyx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sword" {...props}></Icon>
