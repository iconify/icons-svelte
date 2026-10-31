<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocj-w3b2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocj-w3b2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wolf-round" {...props}></Icon>
