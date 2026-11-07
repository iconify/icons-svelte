<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edf2mabxb.css';
import '../../css/y/ybgbmbbwp.css';
import '../../css/z/zty6cw7zo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edf2mabxb"/><path class="ybgbmbbwp"/><path class="zty6cw7zo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-transfer-horizontal-bold-duotone" {...props}></Icon>
