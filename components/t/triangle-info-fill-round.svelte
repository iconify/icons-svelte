<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6uw1bcex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6uw1bcex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:triangle-info-fill-round" {...props}></Icon>
