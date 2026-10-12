<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0ips-hnl.css';
import '../../css/f/f2vy__bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l0ips-hnl"/><path class="f2vy__bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:trash-off-filled" {...props}></Icon>
