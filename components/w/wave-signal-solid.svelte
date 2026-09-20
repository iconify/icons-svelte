<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhcbl6bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vhcbl6bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:wave-signal-solid" {...props}></Icon>
