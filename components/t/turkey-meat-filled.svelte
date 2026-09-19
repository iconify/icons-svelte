<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr7j_s4ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dr7j_s4ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:turkey-meat-filled" {...props}></Icon>
