<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s1tbpzbtk.css';
import '../../css/m/mitzgwbte.css';
import '../../css/u/u7z7qdbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="s1tbpzbtk"/><path clip-rule="evenodd" class="mitzgwbte"/><path class="u7z7qdbes"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:watch-square-bold" {...props}></Icon>
