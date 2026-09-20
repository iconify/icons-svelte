<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dft5_h09g.css';
import '../../css/j/jzfqtdbbl.css';
import '../../css/q/q9cwh3bbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="dft5_h09g"/><path class="jzfqtdbbl"/><path class="q9cwh3bbn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wallet-2-filled" {...props}></Icon>
