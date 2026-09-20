<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw3tawb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bw3tawb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-4-line" {...props}></Icon>
