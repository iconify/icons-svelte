<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw85gbcmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pw85gbcmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:signage-3-solid" {...props}></Icon>
