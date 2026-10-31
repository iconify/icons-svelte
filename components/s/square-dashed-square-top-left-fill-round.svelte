<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doc4jkx1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="doc4jkx1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-dashed-square-top-left-fill-round" {...props}></Icon>
