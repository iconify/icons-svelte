<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b19kkmblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b19kkmblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sparkles-fill-round" {...props}></Icon>
