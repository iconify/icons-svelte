<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jovy96b0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jovy96b0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:virus-fill-round" {...props}></Icon>
