<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/l/l1ojs5toy.css';
import '../../css/e/eh_8t3brt.css';
import '../../css/d/d9f73pbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="l1ojs5toy"/><path class="eh_8t3brt"/><path class="d9f73pbit"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:tag-horizontal-end-percent-sharp-duotone" {...props}></Icon>
