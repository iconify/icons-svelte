<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6_14oact.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6_14oact"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:time" {...props}></Icon>
