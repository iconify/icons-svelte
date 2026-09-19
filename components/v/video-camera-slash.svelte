<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpf68mbvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpf68mbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:video-camera-slash" {...props}></Icon>
