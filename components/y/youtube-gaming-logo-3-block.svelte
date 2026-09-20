<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kltqt2bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kltqt2bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:youtube-gaming-logo-3-block" {...props}></Icon>
