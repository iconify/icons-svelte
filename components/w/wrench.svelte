<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi37w--vt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi37w--vt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:wrench" {...props}></Icon>
