<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mfs8q8gqb.css';
import '../../css/t/t0g5d7bgq.css';
import '../../css/m/ms4raqipz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mfs8q8gqb"/><path class="t0g5d7bgq"/><path class="ms4raqipz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sun-moon-duotone" {...props}></Icon>
