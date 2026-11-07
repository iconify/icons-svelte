<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtmuzrg2o.css';
import '../../css/m/mmtd6l_0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtmuzrg2o"/><path class="mmtd6l_0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-italic-circle-bold-duotone" {...props}></Icon>
