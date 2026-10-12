<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i_3mstbyq.css';
import '../../css/x/xh0qke_up.css';
import '../../css/l/lo2x74bux.css';
import '../../css/c/c_53ogbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i_3mstbyq"/><path class="xh0qke_up"/><path class="lo2x74bux"/><path class="c_53ogbue"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:train-front-duotone" {...props}></Icon>
