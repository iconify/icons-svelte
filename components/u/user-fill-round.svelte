<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr47fgb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zr47fgb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:user-fill-round" {...props}></Icon>
