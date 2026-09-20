<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l7i1k0bst.css';
import '../../css/t/tncwp6bgy.css';
import '../../css/g/gjraafcmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l7i1k0bst"/><path class="tncwp6bgy"/><path class="gjraafcmt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smartphone-2-bold-duotone" {...props}></Icon>
