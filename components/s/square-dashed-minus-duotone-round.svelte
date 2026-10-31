<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sds54fboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sds54fboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-dashed-minus-duotone-round" {...props}></Icon>
