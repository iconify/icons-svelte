<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w-oq9ybmx.css';
import '../../css/w/wk8pa9buv.css';
import '../../css/r/r5euffbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w-oq9ybmx"/><path class="wk8pa9buv"/><path class="r5euffbjm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:trees-duotone" {...props}></Icon>
