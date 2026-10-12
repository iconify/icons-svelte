<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iu-v58ols.css';
import '../../css/f/f71osil0z.css';
import '../../css/s/s4xybibjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iu-v58ols"/><path class="f71osil0z"/><path class="s4xybibjt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:server-duotone" {...props}></Icon>
