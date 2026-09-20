<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps7766bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ps7766bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:slide-share-logo-block" {...props}></Icon>
