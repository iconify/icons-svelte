<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws2eqjbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ws2eqjbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zoom-out-fill-round" {...props}></Icon>
