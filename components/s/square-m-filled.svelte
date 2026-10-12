<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxdpyfbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fxdpyfbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-m-filled" {...props}></Icon>
