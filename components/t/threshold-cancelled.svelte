<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmjqnx2vm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kmjqnx2vm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:threshold-cancelled" {...props}></Icon>
