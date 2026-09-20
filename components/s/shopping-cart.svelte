<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/a/asuw0vbpc.css';
import '../../css/e/ekaoqnb1l.css';
import '../../css/o/o74a4ibec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="asuw0vbpc"/><path class="ekaoqnb1l"/><path class="o74a4ibec"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:shopping-cart" {...props}></Icon>
