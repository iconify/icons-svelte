<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0l6w_fxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s0l6w_fxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:stumble-upong-1ing-logo-block" {...props}></Icon>
