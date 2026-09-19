<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrizf2d8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrizf2d8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:skip-next-circle-filled" {...props}></Icon>
