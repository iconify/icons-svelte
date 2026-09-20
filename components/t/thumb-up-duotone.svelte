<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/djl_9-bta.css';
import '../../css/k/kg3w2bste.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="djl_9-bta"/><path class="kg3w2bste"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:thumb-up-duotone" {...props}></Icon>
