<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/g/ge_-4ubim.css';
import '../../css/n/n2h6fyjip.css';
import '../../css/l/l4j1qrodv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="bi12bsetm"><path class="ge_-4ubim"/><path class="n2h6fyjip"/><path class="l4j1qrodv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:undo-history" {...props}></Icon>
