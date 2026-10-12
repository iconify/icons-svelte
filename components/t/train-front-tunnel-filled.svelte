<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa7izibxv.css';
import '../../css/t/t9gs7gpae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qa7izibxv"/><path clip-rule="evenodd" class="t9gs7gpae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:train-front-tunnel-filled" {...props}></Icon>
