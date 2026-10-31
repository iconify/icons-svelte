<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz0a0j8fe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz0a0j8fe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:triangle-close-round" {...props}></Icon>
