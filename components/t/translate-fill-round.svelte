<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y39qohbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y39qohbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:translate-fill-round" {...props}></Icon>
