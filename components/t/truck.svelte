<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/g/gwf5l3iwb.css';
import '../../css/a/asbceibyx.css';
import '../../css/x/xmr8z2bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gwf5l3iwb"/><circle class="asbceibyx"/><circle class="xmr8z2bep"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:truck" {...props}></Icon>
