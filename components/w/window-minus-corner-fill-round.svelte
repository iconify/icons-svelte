<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2ftvehwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2ftvehwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-minus-corner-fill-round" {...props}></Icon>
