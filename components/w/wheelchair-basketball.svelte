<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy3fjbcsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xy3fjbcsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:wheelchair-basketball" {...props}></Icon>
