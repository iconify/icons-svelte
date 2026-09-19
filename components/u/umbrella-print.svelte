<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/koswg3-pd.css';
import '../../css/v/vzc9z3b4i.css';
import '../../css/f/fcv3ivblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="koswg3-pd"/><path class="vzc9z3b4i"/><path clip-rule="evenodd" class="fcv3ivblv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:umbrella-print" {...props}></Icon>
