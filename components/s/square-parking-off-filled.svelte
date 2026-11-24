<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs_nhrb3i.css';
import '../../css/v/vx68g0b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cs_nhrb3i"/><path class="vx68g0b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-parking-off-filled" {...props}></Icon>
