<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr-v_6l2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vr-v_6l2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sledgehammer-outline" {...props}></Icon>
