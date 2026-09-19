<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lc7wpp7xj.css';
import '../../css/i/ifffufbqi.css';
import '../../css/d/d6zxgccaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#healthiconsSonogramNegative0)" class="cuyn6tgcc"><path class="lc7wpp7xj"/><path clip-rule="evenodd" class="ifffufbqi"/></g><defs><clipPath id="healthiconsSonogramNegative0"><path class="d6zxgccaz"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:sonogram-negative" {...props}></Icon>
