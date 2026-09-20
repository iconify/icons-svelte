<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/epu_tj-1c.css';
import '../../css/g/ghvq8sbip.css';
import '../../css/t/t2b8qbc3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="epu_tj-1c"/><path class="ghvq8sbip"/><path class="t2b8qbc3s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:umbrella-bold-duotone" {...props}></Icon>
