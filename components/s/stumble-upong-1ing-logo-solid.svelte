<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx4m1cb0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tx4m1cb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:stumble-upong-1ing-logo-solid" {...props}></Icon>
