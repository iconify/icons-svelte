<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/l/ld24yvbps.css';
import '../../css/t/t59yavedn.css';
import '../../css/b/bfa9u6b3s.css';
import '../../css/v/vyf_cubjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ld24yvbps"/><path class="t59yavedn"/><path class="bfa9u6b3s"/><path class="vyf_cubjn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:target-arrow" {...props}></Icon>
