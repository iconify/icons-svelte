<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0yu7z-4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0yu7z-4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:text-align-justify-fill-round" {...props}></Icon>
