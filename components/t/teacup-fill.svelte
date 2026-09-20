<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu0f4hb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tu0f4hb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:teacup-fill" {...props}></Icon>
