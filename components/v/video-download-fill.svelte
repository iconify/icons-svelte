<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg6rx7blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg6rx7blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:video-download-fill" {...props}></Icon>
