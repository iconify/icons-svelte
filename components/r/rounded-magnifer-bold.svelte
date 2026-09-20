<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf-a91bde.css';
import '../../css/q/q0zx9pbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xf-a91bde"/><path class="q0zx9pbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rounded-magnifer-bold" {...props}></Icon>
