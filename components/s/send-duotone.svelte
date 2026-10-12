<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e3s5wzb5x.css';
import '../../css/o/o9eo1e7xa.css';
import '../../css/v/v-0f67bvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e3s5wzb5x"/><path class="o9eo1e7xa"/><path class="v-0f67bvu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:send-duotone" {...props}></Icon>
