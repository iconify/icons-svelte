<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/t/tke4h5b0x.css';
import '../../css/s/sumuwdriv.css';
import '../../css/u/ugw1omula.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="tke4h5b0x"/><path class="sumuwdriv"/><circle class="ugw1omula"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:route-off" {...props}></Icon>
