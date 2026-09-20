<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf9ps8npn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bf9ps8npn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:water-drop-1-solid" {...props}></Icon>
