<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd3tyqb5z.css';
import '../../css/r/rvqm-4muf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bd3tyqb5z"/><path class="rvqm-4muf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-mouse-pointer-filled" {...props}></Icon>
