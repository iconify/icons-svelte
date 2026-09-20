<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k09b0rb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k09b0rb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:video-frame-2-linear" {...props}></Icon>
