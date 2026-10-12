<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h0l0t4bnd.css';
import '../../css/o/oi_p53big.css';
import '../../css/v/v7epvdjfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h0l0t4bnd"/><path class="oi_p53big"/><path class="v7epvdjfq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:test-tube-diagonal-duotone" {...props}></Icon>
