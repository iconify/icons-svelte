<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt_whcb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zt_whcb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:tree-deciduous-filled" {...props}></Icon>
