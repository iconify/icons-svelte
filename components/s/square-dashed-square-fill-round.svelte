<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejw8libxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejw8libxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-dashed-square-fill-round" {...props}></Icon>
