<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er0sxpbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er0sxpbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zoom-in-round" {...props}></Icon>
