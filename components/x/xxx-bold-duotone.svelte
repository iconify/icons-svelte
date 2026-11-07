<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg928d-qd.css';
import '../../css/c/chxxm3fvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg928d-qd"/><path clip-rule="evenodd" class="chxxm3fvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:xxx-bold-duotone" {...props}></Icon>
