<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2v64kbha.css';
import '../../css/i/i-hsyrblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d2v64kbha"/><path class="i-hsyrblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tram-bold-duotone" {...props}></Icon>
