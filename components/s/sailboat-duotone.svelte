<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/odr5n16ys.css';
import '../../css/f/fuqcm9bty.css';
import '../../css/g/gnp_skboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="odr5n16ys"/><path class="fuqcm9bty"/><path class="gnp_skboa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sailboat-duotone" {...props}></Icon>
