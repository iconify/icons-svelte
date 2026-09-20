<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/n9a_lybsm.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/n/nv_660ntr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="n9a_lybsm"/><circle class="shu3xdl9q"/><path class="nv_660ntr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-circle-line-duotone" {...props}></Icon>
