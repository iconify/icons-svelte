<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfp_v5kne.css';
import '../../css/o/ow6-kpbfs.css';
import '../../css/q/qcydym7-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfp_v5kne"/><path class="ow6-kpbfs"/><path class="qcydym7-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:streets-bold-duotone" {...props}></Icon>
