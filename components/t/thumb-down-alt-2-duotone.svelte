<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kzig_cb2h.css';
import '../../css/k/kgk1kac4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kzig_cb2h"/><path class="kgk1kac4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:thumb-down-alt-2-duotone" {...props}></Icon>
