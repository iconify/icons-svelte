<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3xjz0bjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3xjz0bjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:scan-duotone-round" {...props}></Icon>
