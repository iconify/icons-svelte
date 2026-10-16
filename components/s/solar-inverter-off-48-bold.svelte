<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-e1u6q-v.css';
import '../../css/y/ysk6l2evj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a-e1u6q-v"/><path class="ysk6l2evj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-inverter-off-48-bold" {...props}></Icon>
