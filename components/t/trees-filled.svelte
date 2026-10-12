<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf-n3jbtm.css';
import '../../css/p/p2xw8f0_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wf-n3jbtm"/><path class="p2xw8f0_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:trees-filled" {...props}></Icon>
