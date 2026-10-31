<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xipc_jbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xipc_jbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:signal-high-duotone-round" {...props}></Icon>
