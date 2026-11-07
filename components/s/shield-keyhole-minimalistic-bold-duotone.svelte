<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaizi48jf.css';
import '../../css/y/yrprrjbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oaizi48jf"/><path clip-rule="evenodd" class="yrprrjbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-keyhole-minimalistic-bold-duotone" {...props}></Icon>
