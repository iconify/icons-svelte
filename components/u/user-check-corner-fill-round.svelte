<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl1vi9b1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zl1vi9b1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:user-check-corner-fill-round" {...props}></Icon>
