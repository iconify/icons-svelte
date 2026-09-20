<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoya6dbao.css';
import '../../css/m/m5l3mnb5w.css';
import '../../css/j/j_tp7ieis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aoya6dbao"/><path class="m5l3mnb5w"/><path class="j_tp7ieis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:security-network-chain" {...props}></Icon>
