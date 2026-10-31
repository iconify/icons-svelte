<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvx9cwb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvx9cwb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:user-lock-corner-round" {...props}></Icon>
