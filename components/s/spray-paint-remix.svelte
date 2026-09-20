<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldr7rolws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ldr7rolws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:spray-paint-remix" {...props}></Icon>
