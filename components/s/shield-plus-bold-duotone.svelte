<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaizi48jf.css';
import '../../css/y/yw53yobjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oaizi48jf"/><path class="yw53yobjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-plus-bold-duotone" {...props}></Icon>
