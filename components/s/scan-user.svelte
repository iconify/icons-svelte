<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/j/jpfl0_i4c.css';
import '../../css/u/urz-4cihd.css';
import '../../css/k/kmt8x7ffq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jpfl0_i4c"/><circle class="urz-4cihd"/><path class="kmt8x7ffq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:scan-user" {...props}></Icon>
