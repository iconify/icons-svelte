<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej_l1ebmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ej_l1ebmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:zap-off-filled" {...props}></Icon>
