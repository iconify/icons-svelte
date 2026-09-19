<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnune9bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bnune9bif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:wallet-alt-02-filled" {...props}></Icon>
