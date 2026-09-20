<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i5firfbkf.css';
import '../../css/o/oim6mdb6p.css';
import '../../css/j/j4sfh2eqn.css';
import '../../css/g/grfxzyb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i5firfbkf"/><path class="oim6mdb6p"/><path class="j4sfh2eqn"/><path class="grfxzyb0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sim-card-bold-duotone" {...props}></Icon>
