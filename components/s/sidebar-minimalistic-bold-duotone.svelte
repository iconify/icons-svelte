<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1nbikbny.css';
import '../../css/e/eaq7c7yzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g1nbikbny"/><path class="eaq7c7yzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sidebar-minimalistic-bold-duotone" {...props}></Icon>
