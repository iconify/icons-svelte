<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc2e3ggwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fc2e3ggwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:transfer-truck-time-remix" {...props}></Icon>
