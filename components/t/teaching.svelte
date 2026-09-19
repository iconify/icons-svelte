<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/w/wtc67qbno.css';
import '../../css/e/ekwamnsnd.css';
import '../../css/e/ep-8rwk8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wtc67qbno"/><circle class="ekwamnsnd"/><path class="ep-8rwk8d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:teaching" {...props}></Icon>
