<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/c/c13q-1-6o.css';
import '../../css/n/npbdvbd7h.css';
import '../../css/x/xnydgsbih.css';
import '../../css/r/rij50zbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="c13q-1-6o"/><path class="npbdvbd7h"/><path class="xnydgsbih"/><path class="rij50zbkr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:zoom-in" {...props}></Icon>
