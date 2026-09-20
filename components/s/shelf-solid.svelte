<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmb8glb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kmb8glb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shelf-solid" {...props}></Icon>
