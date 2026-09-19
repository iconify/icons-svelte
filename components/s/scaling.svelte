<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tmxlmc_fk.css';
import '../../css/m/mo5jszbox.css';
import '../../css/p/p2gcfns7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tmxlmc_fk"/><path class="mo5jszbox"/><path class="p2gcfns7j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:scaling" {...props}></Icon>
