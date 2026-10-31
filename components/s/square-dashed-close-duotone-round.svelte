<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtx1i4byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtx1i4byc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-dashed-close-duotone-round" {...props}></Icon>
